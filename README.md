### Created in Google Colab using Python 3.10.12 (main, Nov 20 2023, 15:14:05) [GCC 11.4.0]
-----------------------------------------------------------------------------

Additional packages installed via pip command in Google Colab

#### pip install beautifulsoup4
#### pip install requests
#### pip3 install seaborn
#### pip install tensorflow==2.9.2
#### pip install keras==2.9.0
#### pip install tensorflow-hub

## OVERVIEW

This is a classification task attempting to classify the levels of support from one or both major parties in the United State Congress for bills brought to the floor and put to a vote using only the text data found in the bill text and the bill title found in the bills. 
The classification task attempts to use the title and text of the bills to classify the level of support in one of the following categories:

* **0 - Not strongly supported by either party**
* **1 - little support from Republicans, strong support from Democrats**
* **2 - moderate support from Republicans, strong support from Democrats**
* **3 - strong support from Republicans, little support from Democrats**
* **4 - strong support from Republicans, moderate support from Democrats**
* **5 - strong support from both parties**

This project was done in two parts, and uses two separate notebooks, although an attempt may be made in the future to consolidate the work in both notebooks for brevity's sake.

### Link to First Notebook - 

https://github.com/EdwardMMiller/Predicting-Party-Support-From-Bill-Text/blob/main/Capstone_I_Using_Bill_Text_To_Predict_Party_Support.ipynb

## Link to Second Notebook

https://github.com/EdwardMMiller/Predicting-Party-Support-From-Bill-Text/blob/main/Capstone_I_Follow_up_workipynb.ipynb
