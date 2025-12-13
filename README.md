# Exploring Music Classification — Composers and Genres

![Project Icon](https://github.com/abarton51/CS_4641_Project/blob/main/assets/images/robotmusic_icon1.png?raw=true)

### Authors
Austin Barton, **Karpagam Karthikeyan**, Keyang Lu, Isabelle Murray, Aditya Radhakrishan

Check out our project website [**here**](https://abarton51.github.io/CS_4641_Project/tabs/midterm.html).

---

## Abstract

Classification as a machine learning task has been thoroughly studied, but **audio data classification** remains particularly challenging. Audio can be represented in multiple ways: as spectrogram PNG images for image-based classification, or as MIDI files parsed into feature vectors.  

The complexity arises from the **small sequential patterns** that distinguish one composer or genre from another. For example, experienced classical musicians can differentiate Bach from Beethoven on previously unheard pieces, while genre enthusiasts can identify sub-genres of metal. We aim to design machine learning models that can learn these subtle distinctions and reliably classify music by **composer and genre**, despite the inherent subjectivity in music labeling.

---

## Features / Highlights

- Processes **audio in multiple formats** (MIDI, spectrogram images)
- Implements **feature extraction pipelines** for machine learning models
- Trains models to classify **both composer and genre**
- Provides **visualizations and analysis** of model performance

---

## Technologies Used

- **Python**  
- **scikit-learn, TensorFlow / PyTorch** (for model building)  
- **Librosa** (audio feature extraction)  
- **Pandas / NumPy** (data manipulation)  
- **Matplotlib / Seaborn** (visualization)

---

## Repository Structure

```
exploring_music_classification/
├── data/             # Raw and processed audio data
├── notebooks/        # Jupyter notebooks for analysis and modeling
├── src/              # Scripts for preprocessing, feature extraction, and training
├── assets/           # Images and figures for README or reports
├── models/           # Saved machine learning models
├── requirements.txt  # Python dependencies
└── README.md         # Project overview
```

---

## How to Run Locally

1. Clone the repo:

```bash
git clone https://github.com/karpagam-karthikeyan/exploring_music_classification.git
cd exploring_music_classification
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebooks in `notebooks/` or scripts in `src/` to reproduce results.

---

## Personal Contribution

**Karpagam Karthikeyan:**  
- Developed data preprocessing and feature extraction pipelines  
- Assisted in model training and evaluation  
- Contributed to README documentation and visualization of results

---

## Future Work

- Experiment with **deep learning architectures** for improved accuracy  
- Expand dataset to include more composers and genres  
- Create a **web interface** for interactive music classification
