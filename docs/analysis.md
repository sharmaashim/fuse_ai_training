## Project Analysis
### User story structure:
=> [Who? -> What? -> Why?]
 
Example:
1. As a buyer, I want good recommendations and quality products at an affordable price .
 
2. As a decisionmaker, I want to classify user's reviews, so that I can better understand market shifts and user’s tastes.
 
### Problem and Solution Formulation
 
#### **What is the problem?**
*Informal description:*
* I need a system that will tell me good or bad reviews about the products.
 
 
#### **Formalism:**
 
* Task(T): Classify the sentiments on the  product reviews.
* Experience(E): A corpus of reviews from the product description forums , chat rooms, etc
* Performance(P): Classification accuracy, Precision , Recall
 
#### **Assumptions:**
 
* The specific words used in the corpus matter to the model.
* The dataset is labelled.
* Sentiments like excited, awesome, affordable, good, etc. refer to good product reviews.
* Sentiments like expensive , less durable , dangerous , etc. refer to bad product reviews.
* The program might not accurately  classify sarcasm posts , slang words and spelling mistakes.
 
 
#### **Similar Problem:**
 
A related problem would be email spam discrimination , tweets sentiments classification that uses text messages as input data and needs classification decision.
 
 
**Why does the problem need to be solved?**
 
*Motivation:*
* In order to  improve customer satisfaction, better sales and market traffic , our system can provide personalized applications to the customer , correctly classify good and bad products according to the user's taste .It will help improve good shopping experience and might guide policy makers where to focus on .  It will help to retain old customers too.
 
 
**How would I solve the problem?**
 
We plan to solve the problem through following steps :
 
* Gather or collect  the product reviews , support ask/ help from forums and chat groups.
* Then Identify the sentiments and tone based on the keywords used in the reviews .
* Then we find out  the products’s popularity , review an user’s taste accordingly from the source of satisfaction/dissatisfaction labels.
* Further management can decide which products to focus on and where to invest more effort for better customer satisfaction.
 
 
**Performance Metrics**
* Performance Metrics are mainly used to measure how effective the model is based on those metrics using test datasets.
 
* The provided dataset , ISEAR dataset contains seven classes of emotion having a balanced number of instances for each class . Thus accuracy metric can be pretty good performance metric for our purpose.
 
* However , various metrics such as Precision, Recall, F1 score, Sensitivity, Specificity, could also be used.

