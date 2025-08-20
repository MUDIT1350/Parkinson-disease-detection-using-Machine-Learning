A Parkinson's disease detection project using the Random Forest algorithm focuses on classifying patients based on features such as voice recordings and motor symptoms.
Random Forest is favored for its strong predictive performance, low overfitting, and interpretability.  
Feature selection techniques optimize the model, achieving accuracy above 95%, aiding early diagnosis effectively.
The model's performance is validated using metrics like accuracy, sensitivity, specificity, and ROC curves, making it a reliable and robust tool for Parkinson's disease detection.
This approach helps in early identification, allowing timely treatment and better patient outcomes.

Prerequisites and steps to run the repository for real time application -:

1. Unzip Image_Dataset
2. Run Voice_Detection on Google Colab , upload all .wav audio files want to run in it
3. Run Drawing_Detection on Visual Studio , download tensorflow in the that folder 

How does the repository works for real time application?

Drawing_Detection model creates parkinson_disease_model.h5 using libraries tensorflow.keras.models , tensorflow.keras.layers , tensorflow.keras.preprocessing.image
Voice_Detection model uses Random Forest Classifier and libraies pydub , pandas , numpy
