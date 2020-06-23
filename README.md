# pytorch_class_competition
A demo of using resnet and cnn to train a flower classification task

The task from a Kaggle competition: https://www.kaggle.com/ianmoone0617/flower-goggle-tpu-classification

The following procedures are implemented:
1. Find a dataset online (an existing dataset from Google images)
2. Explore the datasets to understand the datasets (e.g., flower_class and its distribution among the existing data) and describe the modeling objectives (not for training a good model, but comparing the performances of several models, including self-created one)
  subgoals: to understand what type of data is it: images with labels
            What type of problem is it? classification.
            Exploratory data analysis - plot graphs and answer any questions (what kind of distribution the flower class is)
3. Modeling: try several approaches
   Define a model (network architecture)
   Pick some hyperparameters
   Train the model
   Make predictions on samples
   select the best model for testing data (without classes)
4. Evaluate on test dataset
5. Save the model weights
6. Record the metrics
7. Conclusions - summarize the learning & identify opportunities for future work
