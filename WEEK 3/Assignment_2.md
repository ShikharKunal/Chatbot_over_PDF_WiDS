# Assignment: Sentiment Analysis with LSTM using PyTorch

## Problem Statement

Implement a Sentiment Analysis Model utilizing LSTM networks on the provided dataset. The dataset, named [`reviews.csv`](reviews.csv), consists of textual reviews categorized as either positive or negative. Your goal is to perform preprocessing on the text data and create and train an LSTM-based model for sentiment analysis using PyTorch.

## Dataset

The dataset (`reviews.csv`) contains two columns:
- **Text:** The text content of the reviews.
- **Sentiment:** Positive or Negative labels.

## Task

### 1. Data Preprocessing

- Load the dataset (`reviews.csv`).
- Explore and understand the distribution of sentiment labels.
- Preprocess the text data, including:
    - Tokenization: Break text into individual words or subwords.
    - Remove stop words and punctuations.
    - Padding: Ensure all sequences have the same length.
    - Convert words to numerical indices.
- _Research a little about lowercasing in sentiment analysis and explore the dataset to decide whether you want to include it in the preprocessing step or not._

### 2. Model Building

- Build an LSTM-based model for sentiment analysis using PyTorch.
- Define the architecture of your model, including **embedding layers** and **LSTM layers**.

### 3. Training

- Split the dataset into training and testing sets.
- Train your model on the training set.
- Evaluate the model on the testing set.

### 4. Analysis and Reporting

- Analyze the model's performance using appropriate metrics (accuracy, precision, recall, etc.).
- Report the key findings and any challenges faced during the process.

## Hints and Guides

### Preprocessing Subprocesses

- Create a vocabulary of words and map them with indices.
- Start the indexing from '1' to the number of words, keep '0' for padding.
- LSTMs requires fixed size inputs so pad the shorter ones and truncate the longer words to a certain length.
- Creating a vocabulary and feeding word indices to the embedding layer is a common and effective approach in NLP tasks. It leverages the advantages of continuous word representations while enabling the model to handle varying input sequences.

### Model Building

- Experiment with different hyperparameters (e.g., embedding dimension, LSTM units) to find a suitable configuration.

### Training

- Use an appropriate loss function (e.g., binary cross-entropy) and optimizer (e.g., Adam).
- Monitor the training process by observing metrics such as loss and accuracy.

### Analysis and Reporting

- Provide visualizations (e.g., confusion matrix) to understand the model's predictions.(_Optional_)
- Discuss any challenges faced during training or issues with the dataset.(_Optional_)
- Consider suggesting improvements or modifications based on your analysis.(_Optional_)

## Submission Guidelines

- Submit a **colab** Notebook containing your code and explanations.
- Include visualizations, such as training curves and confusion matrices.(_Optional_)
- Clearly document each step and explain your rationale for the chosen preprocessing techniques and model architecture.

Feel free to explore additional resources or seek guidance from online tutorials. 
> [!TIP]
> Explore different repositories and documentations, avoid using ChatGPT to write whole assignment. :)
