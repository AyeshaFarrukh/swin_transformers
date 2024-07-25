# Self-Supervised Modality-Agnostic Pre-Training of SWIN Transformers

## Table of Contents

- [Project Description](#project-description)
- [Abstract](#abstract)
- [Research Questions](#research-questions)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)
- [Conclusion](#conclusion)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)


## Project Description

This project explores a novel approach for self-supervised modality-agnostic pre-training of SWIN transformers using contrastive learning. The pre-trained model is fine-tuned on downstream tasks to achieve state-of-the-art performance across different modalities such as images, text, and audio.

## Abstract

The proposal aims to leverage contrastive learning to train a transformer-based model on unlabeled data from multiple modalities. The pre-trained model is then fine-tuned on downstream tasks to achieve state-of-the-art performance.

## Research Questions

1. Can SWIN transformers be pre-trained in a self-supervised manner using contrastive learning?
2. Is the pre-trained model transferable to downstream tasks across different modalities?
3. How does the proposed method compare to existing pre-training approaches for SWIN transformers?

## Methodology

The proposed method consists of the following steps:

1. **Data Collection**: Collect a large dataset of unlabeled data from multiple modalities.
2. **Data Preprocessing**: Preprocess the data to extract meaningful representations for each modality.
3. **Contrastive Learning**: Train a SWIN transformer-based model using contrastive learning on the preprocessed data.
4. **Fine-Tuning**: Fine-tune the pre-trained model on downstream tasks to evaluate its performance.

## Expected Outcomes

1. A novel self-supervised modality-agnostic pre-training method for SWIN transformers.
2. State-of-the-art performance on downstream tasks across different modalities.
3. A better understanding of the transferability of pre-trained models across modalities.

## Conclusion

The proposed research has the potential to make a significant contribution to the field of natural language processing. It can be used to train powerful transformer-based models for a wide range of downstream tasks and provide new insights into the transferability of pre-trained models across modalities.

## Project Structure
.
├── data
│   └── DATA
├── images
│   ├── bar_graph.png
│   ├── pie_chart.png
│   ├── line_chat.png
│   └── generated_output.png
├── code.ipynb
└── README.md

- `data/` contains the dataset.
- `images/` contains the generated visualizations.
- `code.ipynb` contains the code to load data, preprocess, and generate visualizations.
- `README.md` is this file.

## Installation

You can run this project using Jupyter Notebook, Google Colab, or Visual Studio Code with a Python environment. Here are the steps for each:

### Jupyter Notebook


```bash
pip install notebook

git clone https://github.com/AyeshaFarrukh/swin_transformers.git
cd swin_transformers

pip install -r requirements.txt

jupyter notebook

```
Open and run the code.ipynb notebook.

### Google Colab

	1.	Upload the code.ipynb notebook and data/ folder to your Google Drive.
	2.	Open Google Colab and load the code.ipynb notebook.
	3.	Modify the paths in the notebook to point to the data in your Google Drive.
	4.	Run the notebook.

### Visual Studio Code

	1.	Install Visual Studio Code if you haven’t already.
	2.	Install the Python extension for Visual Studio Code.
	3.	Clone the repository:

```bash

git clone https://github.com/AyeshaFarrukh/swin_transformers.git
cd swin_transformers

pip install -r requirements.txt
```

Open the code.ipynb notebook in Visual Studio Code and run the cells.

### Usage

#### Data Preprocessing and Visualization:

Open and run the code.ipynb notebook to preprocess the data and generate visualizations.

#### Visualizations

The following visualizations are generated and displayed in the dashboard:

	1.	Bar Graph: Displays the number of training and test images.
	2.	Pie Chart: Shows the data distribution.
	3.	Line Chart: Visualizes the average loss after training.
	4.	generated Images: Shows the generated images by model.

