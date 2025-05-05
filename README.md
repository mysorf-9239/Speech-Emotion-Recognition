# Speech Emotion Recognition (SER)

This project implements a Speech Emotion Recognition system using deep learning techniques. The system can classify
emotions from speech audio files into different categories.

## Project Structure

```
.
├── data.zip/               # Compressed dataset, extract before running the notebook
├── modal.ipynb             # Main Jupyter Notebook: processing, training, and evaluation
├── data_path.csv           # List of audio file paths
├── features.csv            # Extracted audio features (MFCCs)
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

## Setup

1. Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Extract the dataset and place it in the `data` directory.

## Usage

1. Ensure the dataset is placed inside the `data` directory.
2. Mở file notebook `modal.ipynb` bằng Jupyter Notebook hoặc JupyterLab:

```bash
jupyter notebook modal.ipynb
```

3. Run through each cell sequentially to:
- Preprocess and analyze data
- Extract audio features (MFCCs)
- Build and train the LSTM model
- Evaluate and visualize the model performance

## Features

- Audio feature extraction using MFCCs
- LSTM-based deep learning model
- Emotion classification
- Model evaluation and visualization

## Dependencies

- numpy
- pandas
- librosa
- scikit-learn
- tensorflow
- matplotlib
- seaborn
- jupyter