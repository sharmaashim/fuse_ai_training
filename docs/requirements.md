# ISEAR Sentiment and Emotion Analysis
 
## Requirement Gathering:
 
During the first step of this project, we aim to find out and explicitly document the requirements, provided by the client.
 
This requirements gathering is done assuming a client, Daraz Nepal.  The following specifications are gathered by imaginary Interviews, Questionnaires, Observations, etc.
 
#### 1. About the Company?
 
Daraz.com.np; an online shopping site is one of the largest online shopping stores in Kathmandu, Biratnagar, and across the country.
 
In order to know about the client,  about their operational context as well as the domain they operate in, we asked :
 
**1.1. What does your business do?**
 
We are an online shopping platform providing a wide range of products and services.
 
**1.1. What product or service are you selling?**
 
We are focused on product categories such as consumer electronics, fashion, home essentials, groceries, and lifestyle products.
 
**1.1. What are your mission and vision?**
 
Help connecting thousands of sellers with thousands of customers
 
 
 
 
#### 2. Context of Product:
In order to know where the product fits in in their overall scheme of things, we asked :
 
 
 
**2.1. Why do you need this new system? What is the business need?**
 
With the increment in user base ( customers) and scaling up of the products and shipment areas, it became difficult to analyze and review the user feedback , and provide support accordingly. Thus a new system, where user queries are automatically and smoothly analyzed and categorized is required.
 
On the basis of user feedback, reviews, and support queries,  we want to improve the customer experience, create a lasting bond and increase more customers and provide better products and services.
 
 
**2.2. Is there a system in place to do it right now (even if manual)? If so, how is it done right now? Is the process documented?**
 
Right now reviews are read manually, by CRM ( customer relationship management team), labeled, and prioritized manually. Thus it is difficult and time-consuming to obtain feedback and review products.
 
**2.3. What features do you like about your current system?**
 
That even though it is manual and time-consuming, it is very accurate to identify and process user reviews.
 
**2.3. What features don't you like about the current system?**
 
Requires a lot of human effort and labor and thus we can't catch up with market trends and effects on customer satisfaction.
 
#### 3. About the new system/product
 
**3.1. What are the basic, crucial needs of the new software?**
The system should be able to detect positive, neutral, or negative feelings from text, and expressions of emotions like anger, surprise, the excitement of the customers based on the review of the customer on the given product.
 
**3.2. What benefit can the product provide for your customers?**
 
The project can be used to analyze and prioritize the feedback from customers, thus creating a lasting bond, better understanding of customer taste, and would provide quick support for misplaced and faulty goods.
 
 
**3.3. What should be the top priority?**
 
The system should be able to determine the emotion and satisfaction level  of a customer based on the review or comment. Correct classification of sentiments is a must. Would be better if it works for multiple languages and slang words and emojis too.
 
**3.4. What are the acceptance criteria, if any?**
More than 75% accuracy in the validation set of clients would be good for initial runs and must work on multiple classes of emotions.MIght get better along with more user reviews.
 
 
 
#### 4. System Usage
 
**4.1. Which of your staff will be using or involved in the product the most?**
Support teams, Product Quality review teams will be involved in day-to-day tasks. whereas decision-makers might be involved in the long run to decide where the market trend is shifting and sectors to prioritize.
 
 
**4.2. Will the system need to integrate with any other type of software?**
 
Need to be integrated with support chat groups, and review forums of products.
 
 
 
#### 5. About the Data
 
**5.1. What data do you have that might be related, in any way, to the problem being solved?**
 
We have 7446 records of sentences with corresponding labeled emotions in CSV format. The dataset contains 7 classes of emotions: Joy, Fear, Anger, Sadness, Disgust, Shame, and Guilt.
 
 
**5.2. How is the data stored, manipulated right now? What’s your data infrastructure?**
 
The company collects data from various sources like Product reviews, social network websites, forums, analysis, critiques, and more. These collected data are stored in relational database software, PostgreSQL. The data available now is raw and we don’t have any tools or manpower to perform analytics on it.
 
**5.3. Do you have internal data-dedicated teams?**
 
No, we don’t have any data-dedicated teams.
 
 
 
 
#### 6. Caveats
 
**6.1. What are the constraints on the system being built (resourcing, timing, etc)?**
The system must be completed within 6 months of time and will be extensible for further additions or improvements. The total budget allocated to this project is 20 lakhs. The system should be integrable with the existing systems like support chat groups, and review forums of products.
 
**6.1. What is the strategy for your organization? Are there considerations that need to be taken into account?**
 
 
The main strategy of this organization is to provide the best user experience to the customers and maintain its position as a top online e-commerce company. With this system, we plan to enhance the availability and quality of products based on user feedback and comments.
 
