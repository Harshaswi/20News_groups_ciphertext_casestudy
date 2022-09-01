# 20Ciphers_Newsgroups

### Overview

Source : https://www.kaggle.com/competitions/20-newsgroups-ciphertext-challenge/overview <br>
original dataset :http://qwone.com/~jason/20Newsgroups/

* Firstly, it’s all about encryption which means converting readable text to unreadable text.
* The Ciphertext challenge is to find the unreadable text belongs to which group?
* Now what are all the groups? There are 20News groups (20 classes) dataset having a 20000 newsgroup documents.
* This Problem is a multiclass classification problem.
* This problem is not about decrypting the given ciphertext

### Problem Statement
classification of ciphertexts are belongs to respective Newsgroups (classes)

20ciphers_Newsgroups consists of ciphertexts <br>

train_dataset consists of :<br> 
* Ciphertext : An encrypted text of a readable text <br>
* ID         : A unique ID for each ciphertext <br>
* Target     : 20 news groups are present, each ciphertext are belongs to one of the news groups <br>

Test_dataset consists of : <br>
* Ciphertext : An encrypted text of a readable text <br>
* ID         : A unique ID for each ciphertext <br>                               

We need to classify the Target group for given test_dataset ciphertexts.

### what is the use?
* By just using ML classification techniques we are able to classify Newsgroups without using any cryptographh algorithms
* we don't need to use cryptography algorithms to predict the groups ,then How will we classify?
* Machine learning Algorithms are using in Every Domain in real world. so, yes in crytpgraphy also we can use ML classification   technique's like by converting ciphertext into vectors using tfidf ,word2vec and also use some Basic techniques for Feature   
  Engineering.


