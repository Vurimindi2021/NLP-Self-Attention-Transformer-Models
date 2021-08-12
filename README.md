## Impetus - Saving Endangered Languages via AI & NLP/NLI
  Governments can monitorer demographic and political processes of marginalized sections of society. 
![people-of-many-ethnicities-1600x900](https://user-images.githubusercontent.com/78239454/129263372-0b241001-2913-4db7-a7da-67608e0d0bbb.jpg)

# Detecting Contradiction and Entailment In Multilingual Text Using Self-Attention Transformer Models - BERT, DistilBERT and RoBERTa
Training data is pairs of two sentences (consisting of a premise and a hypothesis) classified into three categories Entailment, Neutral or Contradiction. Training data contains premise hypothesis pairs in fifteen different languages, including: Arabic, Bulgarian, Chinese, German, Greek, English, Spanish, French, Hindi, Russian, Swahili, Thai, Turkish, Urdu, and Vietnamese is avaiable at: https://www.kaggle.com/c/contradictory-my-dear-watson/data 

# WordCloud [premise] Frequency of top 500 words in Training Data
![wordcloud_premise](https://user-images.githubusercontent.com/78239454/129213813-bb9f82bb-179b-4301-a874-87943a1346e1.png)

# WordCloud [hypothesis] Frequency of top 500 words in Training Data
![wordcloud_hypothesis](https://user-images.githubusercontent.com/78239454/129213896-e3d3ab5a-e8db-4020-a891-ff54913e52d3.png)

# Length of premise hypothesis pairs in Training Data
![PHsentence Length](https://user-images.githubusercontent.com/78239454/129214303-2d116d02-adf7-4004-be52-8ce9e4288005.png)

# Length of premise hypothesis pairs in Testing Data
![PHsentence Length-testing](https://user-images.githubusercontent.com/78239454/129214397-774d0a2a-60d6-4812-adb7-b6e8a28bb3db.png)

# Language distribution in Training Data 
![language_train_pie (1)](https://user-images.githubusercontent.com/78239454/129109653-7c6b5f5a-ef0c-4d9e-92af-beb32c7982c5.png)

# Label distribution in Training Data 
![Screenshot from 2021-08-12 09-33-15](https://user-images.githubusercontent.com/78239454/129215776-9f9ffdc4-3bdd-4ff2-82a6-404534b95391.png)

# Technologies Used
![Screenshot from 2021-08-12 09-29-11](https://user-images.githubusercontent.com/78239454/129215138-056e2379-995c-4101-b678-8ab7b445db99.png)


# BERT, DistilBERT and RoBERTa model accuracies
![model_accuracy1](https://user-images.githubusercontent.com/78239454/129111082-5653a210-10ea-466c-b592-72adbdcad1a1.png)

# XLM-RoBERTa-Large Confusion Matrix 
![English_CM_XLM_RoBERTa_Large_Aug_Eng](https://user-images.githubusercontent.com/78239454/129112239-13f96343-2d90-4ffe-a1c8-49072fb1df79.png)

# Conclusion
In conclusion XLM-RoBERTa-Large model performed better on English. The accuracies for low resource languages is unsatisfactory. In future, to make this model better I will need to develop more complex Self-Attention Transformer models and see if there are any more hyperparameters that can be tweaked for better performance. So work still in progress.
