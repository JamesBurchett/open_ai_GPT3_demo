# open_ai_GPT3_demo

This project was to build an excercise tracking application with Python and Google Sheets. This will track workouts including distances, time and how many colories burned. 
The inspiration for this came from the GPT3 Open Ai model that uses powerful natural language processing. 

This means that app can take as an input normal English sentence for example the input asks Tell me what excercises you did?: "I ran 5k and cycled for 20 min"
The app will log these activities as will understand that one of the activities was running and one cycling and calculated out duration based on distance and calories.

Generative Pre-trained Transformer 3 (GPT-3) (stylized GPT·3) is an autoregressive language model that uses deep learning to produce human-like text.

It is the third-generation language prediction model in the GPT-n series (and the successor to GPT-2) created by OpenAI, a San Francisco-based artificial intelligence research laboratory.[2] GPT-3's full version has a capacity of 175 billion machine learning parameters. GPT-3, which was introduced in May 2020, and was in beta testing as of July 2020,[3] is part of a trend in natural language processing (NLP) systems of pre-trained language representations.[1]


Code plan and structure:

1) Setup API credentials and Google spreadsheet
2) Get excercise stats with Natural Language Queries
3) Set up Google Sheet with Sheety
4) Save data into Google sheets
5) Autheticate Sheety API
6) Set up environment variables
