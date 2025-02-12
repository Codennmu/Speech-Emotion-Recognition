# Speech-Emotion-Recognition
Speech Emotion Recognition using RAVDESS, CREMA, TESS, and SAVEE Datasets
Description:
This Python notebook presents an in-depth exploration of speech emotion recognition using a combination of the RAVDESS, CREMA, TESS, and SAVEE datasets. Emotion recognition from speech has numerous applications in fields such as human-computer interaction, affective computing, and mental health assessment. This notebook provides a comprehensive overview of the process, from data preprocessing to model training and evaluation.
Key Features:
Utilizes multiple datasets for robustness and diversity in emotion representation.
Demonstrates data preprocessing techniques specific to speech data.
Implements various machine learning and deep learning models for emotion recognition.
Provides thorough evaluation metrics and analysis for model performance assessment.
TO Run this notebook jupyter notebook and python 3.10 or higher is required, along with libraries: NumPy,pandas,librosa,scikit-learn,Keras
**Acknowledgements**
This project utilizes the following datasets:

RAVDESS
CREMA
TESS
SAVEE

**Training & Validation Performance**
The second plot includes two graphs:

**Training & Testing Loss**:
Shows the decrease in loss over epochs, indicating that the model is learning effectively.
Both training and testing losses converge, meaning the model generalizes well and does not overfit.

**Training & Testing Accuracy:**
The accuracy improves steadily, reaching a plateau around later epochs.
The testing accuracy closely follows training accuracy, indicating minimal overfitting.
![traning and validation](https://github.com/user-attachments/assets/905a6021-bbfe-4084-babc-8d8983e0d3bc)

**Confusion Matrix**
The confusion matrix visualizes the model's classification performance across different emotion categories. Each row represents actual labels, while each column represents predicted labels. The diagonal elements indicate correct classifications, while off-diagonal elements represent misclassifications. This matrix helps analyze which emotions the model confuses the most and highlights areas for improvement.

**Key observations:**

The model performs well in recognizing "angry" and "sad" emotions, as indicated by the high values along the diagonal.
Misclassifications are evident between similar emotions like "disgust", "fear", and "happy", suggesting overlapping features in the dataset.
![confusion matrix](https://github.com/user-attachments/assets/087dde48-05d0-465c-b34c-5a00ec7d08d2)

