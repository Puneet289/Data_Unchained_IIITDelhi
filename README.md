# Data_Unchained_IIITDelhi
**Round 1**<br>
<br>
<br>
The data given was pretty clean with a few nuls and with almost no outliers and obviously not much to play with. We applied some ensemble models of catboost and LightGBM and XGBoost after playing around with some of the features. Click [here](https://www.kaggle.com/c/round1-data-unchained/overview) to view the competition's round 1.

------------------------------------------------------------------------------------------------------
<br>
<br>
<br>
<br>
**Round 2**
<br><br><br>
The round 2 was Natural language processing and the data contained blogs and obviously had links in to play for. We created few features and used Sentence transformers and word embeddings to get out the best of the results but could bag out 7th place.Click [here](https://www.kaggle.com/c/data-unchained-round-2/overview) to view the second round.


--------------------------------------------------------------------------------------------------------
<br><br><br><br>
**Round 3**<br><br><br>
Round 3
This round had a very interesting dataset. The Train, Test and Validation folders further contained several folders named with their respective id's. Each id folder had 8 images and a json file. We were supposed to use all the 8 images together to generate the predictions. Link for the data is [here](https://drive.google.com/file/d/1p5xIPI2e362RK9wgKP3NOwO4U6hNh2q1/view?usp=sharing). Go through the data for a better understanding.

Anyways, to solve this problem, we initially used the DenseNet201 pretrained model to generate features out from each image for an id and then combined them into a numpy array. These features were then made to pass through the GRU layers and the Dense layers. We extracted the ouput from one of the hidden layers and trained them using the CatBoost model to generate out submission file.

We secured 1st position in the final and deciding round.
Click [here](https://www.kaggle.com/t/ef5b543a20a3406c812ce036f60105e5) to go to Round 3 on Kaggle.
