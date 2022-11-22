# Team-90
 Team 90's group project GitHub repository for MGT 6203 (Canvas) Fall of 2022 semester.


This project was mainly done on Google Colab and we recommend to run on Colab as well.
- change file paths to local or your Colab folder

Installation is taken care by running the jupyter scripts
- bert.ipynb
- get-senti-data.ipynb

get-senti-data script
- this script is used to get financial tweets from reddit
- we use the reddit API and praw to scrape data
- create a reddit app here: https://www.reddit.com/prefs/apps and enter the keys into the script
 - client_id
 - client_secret
- save data to be run from Bert script

Bert script 
- this script is used to train the model
- download training data from https://huggingface.co/datasets/financial_phrasebank and save into path
- uncomment the training code and run model
- after training, save the model and comment out the training code
- load the saved model and run the script
- load data saved by get-senti-data script


