# Cat and Dog Image Classifier
This project utilizes a Support Vector Machine (SVM) to classify cat and dog images from the Kaggle dataset. Images are loaded, preprocessed, and used to train the SVM model. The model's accuracy is evaluated on a test set, and an example image is predicted with associated probabilities.

## Project Structure
Dataset:Located in D:/dataset/training_set/ with 'cats' and 'dogs' categories.

Data Preprocessing: Images are resized, flattened, and organized into input and output variables.

Model Training: SVM is trained with hyperparameter tuning using GridSearchCV.

Model Evaluation: Accuracy is calculated, and a classification report is generated.

Image Prediction: Example image prediction with probabilities.

## Dependencies
pandas, os, skimage, numpy, matplotlib

sklearn.svm, sklearn.model_selection

## Instructions
Ensure dataset in D:/dataset/training_set/.

Dataset link:- https://www.kaggle.com/datasets/chetankv/dogs-cats-images?resource=download

Run the code to train and evaluate the SVM model.

Modify the path variable for image prediction.

Run prediction section for visualization and model output.

# Results
![dog](https://github.com/manish-kumhar/PRODIGY_ML_3/assets/78205030/c223fc1e-4711-4471-b7c1-7a64ad7bd849)

Feel free to customize for other projects. For queries or improvements, contact me.

Happy coding!
