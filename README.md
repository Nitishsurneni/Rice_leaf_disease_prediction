Rice Leaf Disease Prediction 🌾
In our project, we have proposed the design of an effective model in detecting rice leaf diseases using machine learning and deep learning algorithms. Farmers can take timely remedial measures if they get information about diseases like Bacterial Leaf Blight, Brown Spot, and Leaf Smut at the initial stage.

Key Features:
1. Project Overview
Why This Project?
Rice is an important food crop but diseases pose a very big threat to its production. It assists in early diagnosis of diseases hence minimising loss and increasing yields.
Objective
For the purpose of developing a machine learning model in which images of rice leaf diseases are identified and solutions to reduce are availed.
2. Gathers data and cleans it
Dataset Overview
Healthy rice leaves and with diseases such as Bacterial Leaf Blight, Brown Spot and Smut disease.
Preprocessing
All images were rescaled to the size of 224 by 224 pixels and standardized in the model training process.
Data Augmentation
Applying flipping, zooming, and rotation techniques were used in order to increase dataset size and variability.
Splitting
There was data divided where 80% was for training the system and 20% was for testing.
3. Model Training
Models Used
We experimented with various models, including:
Traditional ML Models: The models used are Support Vector Machine, Decision Tree, K Nearest Neighbour, Random Forest, Logistic Regression, Gradient Boosting and AdaBoost.
Deep Learning Models: VGG16 pretrained and a Proposed Custom CNN.
Best Models
VGG16 fine-tuned and Custom CNN yielded 87.5% accuracy to the training dataset.
4. Results
Performance Summary
SVM: 81.25%
Decision Tree: 56.25%
KNN: 65.62%
Random Forest: 81.25%
Logistic Regression: 78.12%
Gradient Boosting: 65.62%
AdaBoost: 40.62%
Fine-Tuned VGG16: 87.5%
Custom CNN: 87.5%
Confusion Matrices
Further classification of performance measures of the model across classes.
Remedies
The system provides recommendations of possible treatments for the discovered diseases.
5. Demo
Provide an image source, and the system generates the diagnosis and its probability estimate.
And remedies are displayed for the farmer.
