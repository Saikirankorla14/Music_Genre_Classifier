# Music_Genre_Classifier

1. Introduction
The Music Genre Classifier is a machine learning project that automatically identifies the genre of a given audio clip. It leverages audio feature extraction and classification techniques to categorize music into predefined genres, such as rock, jazz, classical, hip-hop, and others.
2. Dataset
Dataset: GTZAN Genre Collection
The GTZAN dataset consists of 1,000 audio tracks each 30 seconds long. It contains 10 genres with 100 tracks each, including blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock.
3. Feature Extraction
We use the Librosa library to extract meaningful audio features from the clips. Commonly extracted features include MFCCs (Mel Frequency Cepstral Coefficients), chroma features, spectral contrast, and zero-crossing rate. These features are used as input to the machine learning model.
4. Model
The classifier can be implemented using algorithms such as Random Forest, Support Vector Machines (SVM), or deep learning models like Convolutional Neural Networks (CNNs). The model is trained on extracted features from the GTZAN dataset and evaluated using accuracy, precision, recall, and F1-score.
5. Installation & Usage
1. Clone the repository.
2. Install dependencies using: pip install -r requirements.txt
3. Place the GTZAN dataset in the `data/` directory.
4. Run feature extraction: python extract_features.py
5. Train the model: python train.py
6. Predict genre of a new clip: python predict.py <audio_file_path>
6. Requirements
- Python 3.8+
- librosa
- numpy
- pandas

Mel Spectrogram:
<img width="1346" height="989" alt="Mel Spectrogram" src="https://github.com/user-attachments/assets/b07e4c6c-e1d8-441a-b714-6a27da479e8b" />

- scikit-learn
- matplotlib
