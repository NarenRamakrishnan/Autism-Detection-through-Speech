# Autism-Detection-through-Speech

This project investigates Autism Spectrum Disorder (ASD) detection using speech. Audio data was sourced from the Dutch ASDBank and CHILDES corpora in the TalkBank repository, containing recordings of children with ASD and typically developing (TD) children. Four audio features—Spectral Centroid, Spectral Rolloff, Zero Crossing Rate, and RMS—were extracted using Librosa and converted into structured dataframes.

Three machine learning models (SVM, Random Forest, and a Neural Network) were trained and evaluated using accuracy, precision, recall, and F1-score. SVM achieved the strongest overall performance. An ablation study was conducted to assess the importance of each feature, revealing Zero Crossing Rate as the most influential for ASD detection. The project highlights the promise of speech-based screening tools and the need for more accessible, high-quality clinical audio datasets.
