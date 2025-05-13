# ChatDB: Using NLP to Connect to DBMS

### Owen Gurley and Shaaz Ali
ChatDB allows users to query SQL and NoSQL databases using natural language.  
This project uses the Gemini API to convert human-readable questions into database queries.

## Step by Step Guide
1. Copy the repository:  
   (https://github.com/shaazali213/DSCI_Project)  
2. Create and activate a virtual environment using Python:
   - make sure to have an ec2 instance available
   - ensure you can connect to your instance in the terminal in pycharm
   - start and stop sql and mongodb as needed in the terminal
   - run either the sql or mongo api file (ensure files have correct ec2 connection command)
   - can enter NLI prompts in the command line
4. Install requirements.txt pip install -r requirements.txt
5. Add Gemini API (seen below)

## API Key

On Mongo_API and SQL_API respectively

locate at the top --- "#api key here"

replace api key like so

genai_client = genai.Client(api_key='your api key goes here') (use 2.0 flash)


## Prerequisites

-Python

-pip

-MySQL installed and started

-MongoDB installed and started

-AWS EC2 Instance
