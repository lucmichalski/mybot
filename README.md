## DIY: BUILD YOUR OWN JARVIS! (AI Chatbot)
### By Subhash Naveen V<br>
Please visit the below blog for referring to the Original article.<br>
https://medium.com/@naveen.vijapurapu/diy-build-your-own-jarvis-7fae3801c49

![Picr_1](https://user-images.githubusercontent.com/25864352/67790253-79b09000-fa9b-11e9-9b6e-eb133253ec3b.png)
<i>Credit — Marvel Studios </i><br>	 

Table of Contents
=================

* [Motivation](#motivation) <br>
* [Problem Statement](#problem-statement) <br>
* [Introduction](#introduction) <br>
* [Different Types of Chatbots –](#different-types-of-chatbots-) <br>
* [Metrics Used/ Referenced:](#metrics-used-referenced) <br>
* [Improvements and Results:](#improvements-and-results) <br>
* [Dialogflow](#dialogflow)
* [ChatterBot](#chatterbot)
* [RASA](#rasa) <br>
* [Slack and IBM Watson Movie Recommendation System](#slack-and-ibm-watson-movie-recommendation-system)
	* [Data Exploration &amp; Pre-Processing](#data-exploration--pre-processing)
        * [Other options for bots](#other-options-for-bots)
* [Conclusion:](#conclusion) <br>
         * [Future Improvements:](#future-improvements) <br>
         * [These are my bot examples:<br>](#these-are-my-bot-examples) <br>
* [References:<br>](#references)


### Motivation
Conversational AI is re-defining the future of Customer Service. I wanted to explore on the options that are available for deploying chatbots and help answer the below questions to help make a difference for start-ups and smaller companies to compete with larger organizations – <br>
 - What is a Chatbot and why is it becoming a Big Deal?
 - How can it be made accessible to all for deploying a chatbot to improve the Customer Satisfaction Index.
 - Are bot messages the new email, when it comes to generating traffic and leads? (Spoiler – Research and Results say ‘Yes!’)
 <br> <br>
 
### Problem Statement 
<br>
What are the options available for creating Personal bots? No single source of information is easily available for comparing the options available for creating bots
Customer wait times through traditional methods and IVRS have long wait times and cause to bad Customer experience and frustration.
How can we look at ways to accelerate and improve customer service by establishing an innovative messaging service across multiple digital platforms
<br>
<br>

### Introduction 

<br>

<p>It is no longer just a figment of Scify imagination on the big movie screens to have an Artificial Intelligent Robot similar to Jarvis for IronMan replying to your queries. And NO, you don’t have to be wealthy rich like Tony Stark either to own one (or one of the big MNC’s). Sounds interesting?? then please continue reading.. <br>
<br>Below we go through some of the popular options for creating AI Chatbots.<br>
<br>But first, let us understand the architecture and the inner working details of a Chatbot.
<br><br>Process flow of NLP (Natural Language Processing) Pipeline:
<br>Most of the chatbots follow the below structure to identify the intent and entity classifications which is fed in to a pre-trained machine learning model to predict suitable responses to the input query. The steps are as follows:

* Text Processing (Input & Output)
	 - Cleaning
	 - Normalization
	 - Tokenization
	 - Stop Word Removal
	 - Part of Speech Tagging
	 - Named Entity Recognition
	 - Stemming and Lemmatization
 - Feature Extraction
	 - Bag of Words
	 - TF-IDF (Term Frequency — Inverse Document Frequency)
	 - Word Embeddings
 - Modeling
	 - The final stage of the NLP pipeline is modeling, which includes designing a statistical or machine learning model, fitting its parameters to training data, using an optimization procedure, and then using it to make predictions about unseen data.<br>
 
![PicR_2](https://user-images.githubusercontent.com/25864352/67790401-b8464a80-fa9b-11e9-8ead-5ce490928517.png)
<i>Credit — Wall-E & Eva characters are Copyrighted by Disney Pixar Studios</i><br>
<br> 
### Different Types of Chatbots –
 * Contextual AI- (Set of Rules or State Machines)
	 * Notifications (Automated messages on expiry or for renewal)
	 * FAQ Chatbots (Hardcoded commonly asked FAQ’s)
 * Conversational AI & Types-
	 * Rule Based ChatBot
	 * Retrieval Based (TF-IDF)
		 * Few of the frequently used models for Chatbots –
		 	 * CNN (Convolutional Neural Networks)
			 * DNN (Neural Networks)
 * Generative Based
 * Deep Learning
	 * RNN (Recurrent Neural Networks)
<br><br>
Now that we understood the inner workings of a chatbot, let us now compare the three poplar options available and used in the industry based on varying degrees of Ease of Use versus Open Source.<br><br>
We will go over Diaglogflow, Chatterbot & RASA as our three options to build chatbots.
<br>
<br> 
### Side by side comparison 
<br>

![pic_compare](https://user-images.githubusercontent.com/25864352/67794424-a1efbd00-faa2-11e9-9eb2-5f1c9ec47c5c.png)
<br>
<br>
Now as we can clearly see, there is no one single solution that fits all, we will go over the details of each of the options and leave it to you to pick the right tool for your needs!<br>
<br>

### Metrics Used/ Referenced: 

<br>

The below metrics can be considered while deploying a chatbot and analysing the gains<br>

 - Customer Satisfaction
 - Reduction in Customer Wait Times
 - Effective Utilization of key personnel
 - Retention Rate - Effectiveness through Engagement and Re-engagement
 - Reduction in repetitive FAQ's asked freeing up employee's time for other critical tasks
 - Repetitive tasks and human intervention 

<br><br>

 - Market Research on Metrics–
	 - When tested whether its chatbot or email marketing drove more traffic to its website, the results were staggering. On average, 	the bot had an 84% “read” rate and a 53% CTR –  1,428% higher engagement rate than the email funnel.
	 - Though its email content and bot content were both super-personalized, bot appeared to have avoided the spam filters and “inbox fatigue” that led to the lower email metrics.
	 - Automated qualification and immediate response time increased new leads by 70% and new opportunities by 170% in three months.

<br> <br>

### Improvements and Results: 
<br>
- Improved Customer Service
- Improved Customer Engagement
- 6-8 minute average conversations
- 11 turns per conversation
- 50% user re-engagement
- Always Available (24 X 7)
- Reduction in wait times for Customers
          - FAQ Chatbot Reduces Customer Support Emails by 83%
- Data for insights and lead generation
          - Van Leasing Sales Chatbot Generates 30,000+ Leads
- Scalability
- Cost Savings
- Bot saves 950 minutes of Human Time per day
- Enables smaller start-ups to compete against larger more established Organizations
- Chatbots can be a great back up for employees for relatively basic and repetitive tasks being cost-effective, easy to implement, maintain and use.
          - Recruitment Chatbot Reduces Unqualified Job Applications by 73%
<br>
<br>
Courtesy:<https://socialmediaweek.org/newyork/events/case-study-national-geographics-albert-einstein-chatbot/>
	<https://www.ubisend.com/case-studies>

<br>

![PicR_3](https://user-images.githubusercontent.com/25864352/67790251-7917f980-fa9b-11e9-9744-932aec3d61b2.png)


<br>
<br>

### Dialogflow

Dialogflow (formerly Api.ai, Speaktoit) is a Google-owned developer of human–computer interaction technologies based on natural language conversations.
Gives users new ways to interact with your product by building engaging voice and text-based conversational interfaces, such as voice apps and chatbots, powered by AI. Connect with users on your website, mobile app, the Google Assistant, Amazon Alexa, Facebook Messenger, and other popular platforms and devices.
<br><br><p>Dialogflow is an end-to-end, build-once deploy-everywhere development suite for creating conversational interfaces for websites, mobile applications, popular messaging platforms, and IoT devices.
<br><br><p>Natural language understanding recognizes a user’s intent and extracts prebuilt entities such as time, date, and numbers. You can train your agent to identify custom entity types by providing a small dataset of examples. You can also use 40+ prebuilt agents as templates.<br><br>
<p>In September 2014, Speaktoit released api.ai (the voice-enabling engine that powers Assistant) to third-party developers, allowing the addition of voice interfaces to apps based on Android, iOS, HTML5, and Cordova. The SDK’s contain voice recognition, natural language understanding, and text-to-speech. api.ai offers a web interface to build and test conversation scenarios. The platform is based on the natural language processing engine built by Speaktoit for its Assistant application. Api.ai allows Internet of Things developers to include natural language voice interfaces in their products.
<br><br><p>Dialogflow now does sentiment analysis for each user query, powered by Cloud Natural Language. Sentiment analysis scores can be used to hand off unsatisfied users to live agents, or to get a better understanding of which intents lead to the highest customer sentiment.
<br><br>References: https://www.diagflow.com<br>
Wikipedia: Dialogflow<br>

<br><br>

![PicR_4](https://user-images.githubusercontent.com/25864352/67790250-7917f980-fa9b-11e9-84b5-da2feabc9ff0.png)

<br>

### ChatterBot

is a machine-learning based conversational dialog engine build in Python which makes it possible to generate responses based on collections of known conversations. The language independent design of ChatterBot allows it to be trained to speak any language.
<br><br>

__How it works__<br><br>
An untrained instance of ChatterBot starts off with no knowledge of how to communicate. Each time a user enters a statement, the library saves the text that they entered and the text that the statement was in response to. As ChatterBot receives more input the number of responses that it can reply and the accuracy of each response in relation to the input statement increase. The program selects the closest matching response by searching for the closest matching known statement that matches the input, it then returns the most likely response to that statement based on how frequently each response is issued by the people the bot communicates with.
<br><br>

![PicR_5](https://user-images.githubusercontent.com/25864352/67790249-7917f980-fa9b-11e9-8ff4-b6ffe0578a8f.png)<br>

__References__:<br><br>
https://github.com/gunthercox/ChatterBot <br><br>
https://chatterbot.readthedocs.io/en/stable/ <br><br>

![PicR_6](https://user-images.githubusercontent.com/25864352/67790248-787f6300-fa9b-11e9-80f8-7f5cba47ab5d.png)

<br><br>

### RASA

<br>
__RASA__ is a set of open source Machine learning tools for developers for Conversational AI. An open source machine learning framework to automate text-and voice-based conversations.
<br><br>
<p>Rasa’s primary purpose is to help you build contextual, layered conversations with lots of back-and-forth. To have a real conversation, you need to have some memory and build on things that were said earlier. Rasa lets you do that in a scalable way.
<br><br>
Rasa contains two main components:
 * NLU — Natural Language Understanding for Intent Classification and Entity extraction
	 * Takes unstructured data and converts them to structured data on the form of intents and entities
 * Core — Framework for machine learning based, contextual decision making. Dialog Management component. Brains of the Conversational AI
<br><br>
Tutorial:<br>
https://rasa.com/docs/rasa/user-guide/rasa-tutorial<br><br>
Try RASA

![PicR_7](https://user-images.githubusercontent.com/25864352/67794516-c8adf380-faa2-11e9-9c40-d3998e9d7644.png)

<br><br>
__Reference__: https://rasa.com/<br>
__GitHub__: https://github.com/rasaHQ/
<br><br>

### Slack and IBM Watson Movie Recommendation System

<br>
This bot has been created as a separate reposistory to keep the folder structure clean and un-cluttered.

<br>
#### Please refer the below repo for the code implementation and installation instructions.
https://github.com/VijapurapuS/Chatbot/tree/master/bot

<br>

Data Exploration, Pre-processing, Results and Future improvements will be covered here for completeness of the article and Project report.
<br>
One important thing to note with this design is that, the data and processing is all handled in the local system. Even though we use IBM, it is used as an API service and none of the internal data is sent to IBM. This way the entire design can be implemented in your workplace without having to worry about data transfers.
<br>

Users can interact with the bot via Slack. Once the user post a question, it is passed to the backend system for analysis.

All the natural language processing happens in step 2. This includes IBM Watson processing, similarity search, recommendation based on collaborative filtering. After the NLP processing is completed, we have three outputs from it
Intents — What the user is trying to ask or query?
Entities — What is the exact field or column they are looking for?
Dialog/Interaction — Provide the appropriate request/response for the user question.

The results obtained from the backend is posted to user via Slack

### Installation and Bot Setup Implementation & Refinement from Other bots created (DiagFlow & Chatterbot)
This file will walk you through the steps to setup your bot. Download the entire folder and the follow the steps below. 

__Step 1__: 
Create Slack Bot user

__Step 2__: 
Create a IBM Watson account and Upload the bot.json workspace

__Step 3__: 
Install the required packages listed in the requirements.txt file. To install the required packages, please use the code below.

```
pip3 install -r requirements.txt
```
<br>
It would be recommended to use Python 3.5.x or 3.6.x version for this project.

__Step 4__: 
Update the config files with the Slack and Watson API details
Please make sure that you modified the API details both for Slack and Watson in the config.py file

__Step 5__:
Download data from source and perform Data Preparation.
The data for this example is downloaded from the location below:

https://www.kaggle.com/rounakbanik/movie-recommender-systems/data

Name of the dataset - movies_metadata.csv

"metadata_prep.csv" will be created after you run the data preparation code which will be later used in nlp models to train the movie recommendation system.

__Step 6__: 
Create "onetime.txt" file
Navigate to the folder where the main.py file resides and execute the code below.

```
python3 nlp/nlp_solutions/onetime_run_file.py
```
This will create the "onetime.txt" file automatically.

__Step 7__: 
Initiate Bot
Navigate to the folder where the main python script exists and run the code below.

```
python3 main.py
```

### Data Exploration & Pre-Processing

Please refer to the data folder under the repo - https://github.com/VijapurapuS/Chatbot/tree/master/bot for code to follow along.


The data for this exercise is taken from the Kaggle link below. The name of the dataset is “movies_metadata.csv”.
https://www.kaggle.com/rounakbanik/movie-recommender-systems/data?source=post_page-----7c69af7a7439----------------------

The dataset contains a lot of information related to movies with less preprocessing required from users. Hence I chose it for training the 
bot.

Data_Preparation.ipynb <https://github.com/VijapurapuS/Chatbot/blob/master/bot/data/Data_Preparation.ipynb>

<br>

### Other options for bots 
<br>

 - Chatscript
 - Chattypeople
 - Pandorabots
 - Botsify
 - Rebot.me
 
<br>
<br>

### Conclusion:

<br>
Hope this article has simplified the process for creating your own bot! Message me in the comments with your example bots for interaction.
<br><br>

### Future Improvements:
* Improvement based on the language of the film
* Extend recommendations based on actors
* Collaborative user based recommendations

### These are my bot examples:<br>
 * Chatterbot — <https://shankachakra.pythonanywhere.com/> <br>
 * Dialogflow bot <https://bot.dialogflow.com/dialogflow-demo>

<br><br>
### References:<br>
Udacity Nano Degree for Data Scientist <br>
Searches on stackoverflow.com for research<br>
<https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code>
<https://www.kaggle.com/rounakbanik/the-movies-dataset>
<br><br>
