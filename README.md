# NoSQL-challenge

## Overview
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. The requirement here is to evaluate some of the ratings data in order to guide food critics or journalists make informed decisions. 

## Purpose
This challenge was meant to help me explore the NoSQL type of document database called MongoDB. Through the command line code on Terminal I was able to create the database that had a JSON type collection. I was able to create a client connection with the datbase through a PyMongo command to load the collection and store it to a variable. 

I was able to perform exploratory analysis on the collection by examining different aspects of the data stored in the documents in the collection.

#### Part 1: Database and Jupyter Notebook Set Up

In this part, we are connecting to a database through PyMongo by creating an instance of Mongo Client. Upon successfull connection, we then import the data into pandas dataframe for further steps. 

#### Part 2: Update the Database

In this part the data is updated based on the provided criteria and upon verification of proper updation, the data is then stored back into the database for further analysis. 

#### Part 3: Exploratory Analysis

There were specific questions to be answered, which aids in finding the locations that are to be visited and/or avoided.

## Instructions
Follow the steps below to successfully run the code:
1. Clone the repository to your local machine.
2. In the command prompt, navigate to the /Resources folder where the establishments.json file is located.
3. Run foloowing command to import the data from Terminal:
    Import the dataset with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
4. Run the server on the command prompt:
   For Mac: brew services stop mongodb-community@6.0
   For Windows: C:\Program Files\MongoDB\Server\6.0\bin\mongod.exe" --dbpath="c:\data\db

I was able to successfully update the database to insert a new document as well as change the datatypes of certain fields in all the documents in the collection.

I was able to perform exploratory analysis on the collection by examining different aspects of the data stored in the documents in the collection. After obtaining the results to different queries based on the data of interest, I was able to capture the results in Panda Data Frames to match the desired outputs. 
