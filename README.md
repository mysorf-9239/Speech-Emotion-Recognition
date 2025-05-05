# Speech Emotion Recognition (SER)

This project implements a Speech Emotion Recognition system using deep learning techniques. The system can classify
emotions from speech audio files into different categories.

## Project Structure

```
.
├── modal.ipynb             # Main Jupyter Notebook: processing, training, and evaluation
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

3. Download and extract the dataset:
   - [Google Drive - Dataset](https://drive.google.com/file/d/133nvHm8XLbU20nZZhziyYMPjHBC5Xu5g/view?usp=sharing)
   - Extract to a folder named `data` in the project root.

4. (Optional) Download and extract the preprocessed CSV files:
   - [data_path.csv (Google Drive)](https://drive.google.com/file/d/1TGxYRKYuwxkJQnF9ebF_VnC-VECs5h44/view?usp=sharing)
   - [features.csv (Google Drive)](https://drive.google.com/file/d/1RVzlehaiFg86fbMp9lBH5mhrNBXtsN3e/view?usp=sharing)

   Place both files in the root directory of the project.

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