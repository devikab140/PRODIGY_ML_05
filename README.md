# Food Recognition Model
Develop a model that can accurately recognize food items from images and estimate their calorie content, enabling users to track their dietary intake and make informed food choices.

## Data Preparation:

Utilizing the Food-101 dataset containing a diverse collection of over 100,000 food images categorized into 101 classes. Images are organized into folders by food type.

## Image Loading and Labeling:

Implementing a function to load images, resize them (e.g., to 64x64 pixels), and gather them into arrays. Labels (food categories) are extracted correspondingly for each image.

## Label Encoding:

Encoding food category labels into integers using LabelEncoder to prepare for machine learning model training.

## Train-Test Split:

Dividing the dataset into training and testing sets using train_test_split. Training data is used to train the model, while testing data evaluates its performance.

## Model Training:

Training the model over 100 epochs, monitoring loss and accuracy throughout the training process.

## Model Saving:

Saving the trained model for future use.

## Calorie Estimation Model

## Regression Model Setup:

Developing a regression model for predicting calorie values based on recognized food categories. Architecture includes convolutional layers, max-pooling layers, and fully connected layers. The output layer comprises a single neuron without activation for regression purposes.

## Training and Evaluation:

Splitting data into training and testing subsets for calorie prediction. The model is trained to estimate calorie values from food images, and its performance is assessed using Mean Absolute Error (MAE).

## Model Saving:

Once trained, saving the calorie estimation model as "calorie_model.task5" for future applications.

## Contact
For any questions or feedback regarding the project, please feel free to contact me via the email provided below.

- <a href="https://www.linkedin.com/in/devika-b-826637288/"> Devika B (LinkedIn)</a>

- E-mail:- devikab140@gmail.com

