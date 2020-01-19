# Predicting-Avocado-Price-with-LSTM
In this project, I created a Avocado Price prediction model using the Avocado price dataset from Kaggle. LSTM is used for prediction model. The code with all details are provided in Jupyter notebook in the repository.

#### Data:
The dataset has 169 rows of avocado pricing data per region comprising over 2015,2016,2017 and 2018. Half of those records are for conventional avocadoes and rest for organic avocadoes. The data is provided for 54 regions. For simplicity, I only made model for Albany, for conventional avocadoes. Also because we cant make a general pricing model for all states, it wouldnt make sense. The viewers are free to change the name of state or predict price for organic avocadoes to play around with data.

#### Result:
Following training vs validation loss curve is observed for the model:

![image](https://user-images.githubusercontent.com/41015749/72690753-5b33c100-3aed-11ea-94c7-fff62c375a00.png)

After fitting the model, following curve between predicted prices vs actual test set prices is observed.

![image](https://user-images.githubusercontent.com/41015749/72690681-bdd88d00-3aec-11ea-98ed-91653cebedca.png)

### Conclusion
The model fits good but it would have fitted better if we had more data. Instead of weekly pricing for 169 records for 4 years, if we had daily pricing or maybe more data, then a better price prediction model could have been made. Still this project serves as a good practice for me for dealing with sequential data. 
