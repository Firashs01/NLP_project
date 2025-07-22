# NLP Project: Hate Speech and Abusive Language Classification

This project focuses on the classification of hate speech and abusive language in Tunisian Arabic text. It utilizes various NLP techniques for data preprocessing, augmentation, and classification.

## Dataset

The primary dataset used in this project is the Tunisian Hate Speech & Abusive Language (T-HSAB) dataset. The dataset is available in the following files:

- `T-HSAB.xlsx`: The original dataset in Excel format.
- `T-HSAB_csv.csv`: The dataset converted to CSV format.
- `T-HSAB_csv_h.csv`: The dataset in CSV format with a header.

## Project Structure

The project is organized into the following files:

- **Data Files:**
    - `data.csv`: The raw dataset used for processing.
    - `clean_data.csv`: The dataset after cleaning and preprocessing.
    - `aug_noise.csv`: The dataset augmented with noise for robust training.
    - `stopword.csv`: A list of stopwords used for text cleaning.

- **Jupyter Notebooks:**
    - `Clean_data.ipynb`: This notebook contains the code for cleaning and preprocessing the raw data.
    - `noise.ipynb`: This notebook contains the code for data augmentation by adding noise to the dataset.
    - `Ngram_Classification.ipynb`: This notebook implements a classification model using N-grams as features.
    - `classificationdata.ipynb`: This notebook contains the code for the main classification task.
    - `THSABstatic.ipynb`: This notebook performs a static analysis of the T-HSAB dataset.
    - `Untitled.ipynb`: An additional notebook for exploratory analysis.

## Methodology

The project follows these steps:

1. **Data Loading and Exploration:** The T-HSAB dataset is loaded and analyzed to understand its characteristics.
2. **Data Cleaning and Preprocessing:** The text data is cleaned by removing irrelevant characters, and stopwords. The `Clean_data.ipynb` notebook contains the implementation of this step.
3. **Data Augmentation:** To improve the model's performance and robustness, the dataset is augmented by adding noise. The `noise.ipynb` notebook contains the implementation of this step.
4. **Feature Engineering:** N-grams are used as features for the classification model.
5. **Model Training and Classification:** A machine learning model is trained to classify the text as hate speech, abusive, or normal. The `Ngram_Classification.ipynb` and `classificationdata.ipynb` notebooks contain the implementation of this step.

## How to Use

To run this project, you can execute the Jupyter Notebooks in the following order:

1. `Clean_data.ipynb`: To preprocess the raw data.
2. `noise.ipynb`: To augment the dataset.
3. `Ngram_Classification.ipynb` or `classificationdata.ipynb`: To train and evaluate the classification model.

## Dependencies

The following Python libraries are required to run the notebooks:

- pandas
- numpy
- scikit-learn
- nltk
- jupyter

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn nltk jupyter
```
