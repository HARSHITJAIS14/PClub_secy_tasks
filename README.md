#  PClub_secy_tasks
## Task 2: Machine Learning
### Data Collection
a.First of all i went on kaggle to search for all the data related to lung and lung capacity from there i got a dataset of lung capacity link- https://www.kaggle.com/datasets/sulaimanahmed/lung-capacity-data <br> 
b.Then i did research b/w relation of lungcapacity with tidal volume and weight with tidal volume link-https://journals.lww.com/ccejournal/fulltext/2021/05000/ impact_of_height_estimation_on_tidal_volume.13.aspx   and also used ideal body weight and then used both these estimation to avereage . <br>
c.deleted all the unnecessary columns from the dataset and dealt with null values.  <br>
### Applying algorithms.
a.I used cross validation as the main criteria for choosing the best regression model. <br>
b.models used=Linear Regression,Ridge,ElasticNet, SVR regressor,RandomForestRegressor ,Polynomial Regression <br>
c.best model was lineaer regression
### Applying linear regression on tensorflow
a.defined a dense layer with 1 unit and input dim=8 got and r2 score of 88% <br>


## Task3: Computer Vision
### Data Collection
At first tried to find the dataset but never got mask faces with male female label so i tried to apply mask using a project by someone on git didn't workout and then i searched again for the dataset and found it. <br>
### Making Tensorflow cnn model and training over it
used conv2d ,maxpool ,and Dense and flatten in a sequential model as a architecture for the model and then deployed the gradio interface
got an accuracy of 93% on test data <br>
<br> also tried to make a gradio interface
### for best view visit kaggle link --- https://www.kaggle.com/code/harshitjais14/task3-ipynb

## Task2:NLP
### Data preprocess
First i have converted the paragraphs to sentences and stored them in another dataframe . <br>
### Applying nlp
a.used the knowledge of semantic learning and applied it using link-https://www.sbert.net/examples/applications/semantic-search/README.html <br>
b. made functions to answer query using bert model and also to list top 5para and then integrated them to make an interactive session with user <br>
c. made a gradio interface where one can put query and get an answer and the top 5 paragraphs <br>
### for best view visit kaggle link --https://www.kaggle.com/code/harshitjais14/querysearch
