#  PClub_secy_tasks
## Task 2: Machine Learning
### Data Collection
a.First of all i went on kaggle to search for all the data related to lung and lung capacity from there i got a dataset of lung capacity link- https://www.kaggle.com/datasets/sulaimanahmed/lung-capacity-data 
b.Then i did research b/w relation of lungcapacity with tidal volume and weight with tidal volume link-https://journals.lww.com/ccejournal/fulltext/2021/05000/impact_of_height_estimation_on_tidal_volume.13.aspx   and also used ideal body weight and then used both these estimation to avereage .
c.deleted all the unnecessary columns from the dataset and dealt with null values.
### Applying algorithms.
a.I used cross validation as the main criteria for choosing the best regression model.
b.models used=Linear Regression,Ridge,ElasticNet, SVR regressor,RandomForestRegressor ,Polynomial Regression
c.best model was lineaer regression
### Applying linear regression on tensorflow
a.defined a dense layer with 1 unit and input dim=8 got and r2 score of 88%


## Task3: Computer Vision
### Data Collection
At first tried to find the dataset but never got mask faces with male female label so i tried to apply mask using a project by someone on git didn't workout and then i searched again for the dataset and found it.
### Making Tensorflow cnn model and training over it
used conv2d ,maxpool ,and Dense and flatten in a sequential model as a architecture for the model and then deployed the gradio interface
got an accuracy of 93% on test data


## Task2:NLP
### Data preprocess
