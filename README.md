# Assignment9
name :suneel kumar reddy

user id: sxk66390

student id: 700756639

video link:https://drive.google.com/file/d/1F3azIg2934YWe08hthN6ZB16DKb6Nk-x/view?usp=drive_link


In this code, we first create fundamental packages like as pandas and numpy for loading dataframes and datasets, as well as matpotlib for data visualization. We also import a package for regular expressions. In this case, Labencoder is also utilized to transform categorical to numerical data.We are importing a drive from the Google Colab platform so that we can access the stuff on it. We are also loading the dataset as a dataframe and selecting only necessary columns text and sentiment and keeping only necessary columns and removing retweets before tokenizing the sentence and taking values to the feature matrix, padding the feature matrix, and using the dimension of the embedded layer as 128, and long short term memory layer neurons as 196, as well as employing a sequential neural network with an input dimension of 2000 neurons and an output size of 128 neurons. After we have finished building the model and published the model summary. Following that, we apply label encoding to the label matrix and then fit the model, using 67 percent of training data and 33 percent test data split and batch size of 32 then we use a function call to sequential neural network then we evaluate the model and print the accuracy of the model then we save the model and use the saved model to predict on new text data then we save the model then we import the model Then we apply GridSearchCV on the source code provided in the class before summarizing the findings.
