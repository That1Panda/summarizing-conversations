# Summarization Model Evaluation and Fine-Tuning

## Project Overview

This project aims to evaluate the performance of a pre-trained summarization model using a variety of evaluation metrics. The primary focus is on fine-tuning the model to improve its performance on the summarization task. By following the steps in the provided notebook, you will be able to load the model, assess its performance, fine-tune it, and compare different metrics to track its progress.

## Features

- **Model Evaluation**: Assess the performance of the summarization model on the test data using various metrics like ROUGE & BLEU.
- **Fine-Tuning**: Fine-tune the pre-trained model to improve the quality of generated summaries.
- **Metric Comparison**: Compare multiple metrics to obtain a holistic view of the model’s performance.
- **Notebook-Based Workflow**: The entire process is encapsulated in a Jupyter notebook for ease of use.

## Getting Started

To get started with this project, follow the instructions below to install the necessary dependencies and walk through the notebook.

### Prerequisites

Make sure you have the following installed:

- Python 3.7 or higher
- Jupyter Notebook

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/That1Panda/summarizing-conversations.git
   ```

2. Navigate to the project directory:

   ```bash
   cd summarizing-conversations
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Run the Notebook

After installing the dependencies, simply run the Jupyter notebook to follow the steps for model evaluation and fine-tuning:


## Evaluation Metrics

The notebook uses various evaluation metrics to assess the model’s performance:

- **ROUGE** (Recall-Oriented Understudy for Gisting Evaluation)
- **BLEU** (Bilingual Evaluation Understudy)

## Fine-Tuning Process

The fine-tuning process involves adjusting the model's parameters using `SamSum` dataset, allowing for improved results over the pre-trained model.

## Acknowledgments

- [Natural Language Processing with Transformers by Lewis Tunstall, Leandro von Werra, Thomas Wolf](https://www.oreilly.com/library/view/natural-language-processing/9781098136789/) for the Book that guided me through the project

