Sure, here's the updated README file based on the provided information:

---

# ContractNLI Natural Language Inference Project

## Overview
This project aims to perform natural language inference (NLI) on contract documents using pre-trained transformer-based models. The dataset used, ContractNLI, facilitates document-level NLI on contracts to automate and support contract review processes.

## Dataset Description
The ContractNLI dataset contains contracts along with sets of hypotheses. For each hypothesis, the task is to classify whether it is entailed by, contradicted by, or neutral to the contract. Additionally, the system needs to identify evidence spans in the contract supporting the decision.

Dataset Link: [ContractNLI Dataset](https://stanfordnlp.github.io/contract-nli/)

## Tasks
### 1. Data Preparation and Exploration
- **Task**: Check dataset statistics and design train/test/validation sets.
- **Approach**: Utilize data exploration techniques to understand the dataset distribution and prepare data splits for training, validation, and testing.

### 2. Natural Language Inference (NLI)
- **Task**: Perform NLI using two transformer-based approaches.
- **Approach**: Fine-tune pre-trained models such as DeBerta using the training dataset and evaluate their performance on the validation and test sets.

### 3. Performance Analysis and Error Evaluation
- **Task**: Analyze the performance of the models and conduct error analysis.
- **Approach**: Examine the results of the NLI models, identify potential reasons behind errors, and propose improvements.

## Dependencies
- `numpy`: For linear algebra operations
- `pandas`: For data processing and CSV file I/O
- `json`: For handling JSON files
- `matplotlib.pyplot`: For data visualization
- `transformers`: From Hugging Face for using pre-trained models
- `torch`: For deep learning and neural network operations
- `sklearn.metrics`: For evaluating classification performance metrics
- `sklearn.model_selection`: For splitting the data into training and testing sets