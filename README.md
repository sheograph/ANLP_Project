# Neural Detection of AI-Generated Text

## Main Goal

The main goal of this project is to develop and evaluate a neural model for the detection of AI-generated text in a provided dataset.

## Project Timeline

### Dataset Exploration (7.11 - 14.11)

- Analyze the provided dataset format (e.g., tar bz2 archives with .txt files inside).
- Understand the preprocessing applied to the data (e.g., tokenization, BPE encoding).
- Identify any specific challenges in the dataset.

### Data Preprocessing and Split (14.11 - 21.11)

- Preprocess the dataset to make it suitable for training a detection model.
- Split the dataset into training, validation, and test sets.

### Model Selection and Architecture (21.11 - 28.11)

- Choose an appropriate neural architecture for AI-generated text detection.
- Decide on hyperparameters and model configuration.

### Model Training (28.11 - 12.12)

- Train the selected model using the training dataset.
- Fine-tune the model to optimize its performance.

### Model Evaluation (12.12 - 19.12)

- Evaluate the model's performance on the validation set.
- Fine-tune the model based on validation results.
- Test the final model on the test dataset to assess its generalization.

### Documentation and Reporting (19.12 - 26.12)

- Document the project, including the model architecture, hyperparameters, and preprocessing steps.
- Prepare a report summarizing the findings and challenges encountered.
- Create a presentation for sharing the project results.

## Language

The project will be conducted in English.

## Dataset

The project will use the provided dataset, which includes train.tbz2, validation.tbz2, and test.tbz2 files.

## Model/Approach

The project will utilize a neural model suitable for text classification, such as LSTM (Long Short-Term Memory), BERT (Bidirectional Encoder Representations from Transformers), or GPT (Generative Pre-trained Transformer).

## Evaluation Metrics

The project will use the following evaluation metrics:

- Accuracy
- Precision, Recall, F1-score
- ROC-AUC (Receiver Operating Characteristic Area Under the Curve)

## References

- BPE Encoding: [arXiv:1508.07909](https://arxiv.org/abs/1508.07909)
- Subword-NMT: [GitHub Repository](https://github.com/rsennrich/subword-nmt)
- Similar Projects on Text Classification and AI Detection for inspiration.

This README provides an overview of the project plan for detecting AI-generated text. It outlines the project's main goals, timeline, dataset, model, and evaluation metrics.
