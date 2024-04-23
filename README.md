# Information-Retrieval-System
Repository for an information retrieval system. This repository will also be submitted for my CS 429 project.

# Project Write Up

# Abstract
Development Summary: This project involves the creation of an information retrieval (IR) system designed to process and analyze web documents to extract and index content effectively. The system utilizes Python libraries such as Scrapy for crawling web pages, sklearn for processing data, and Flask to set up a web interface. While the project is unfinished, and there are still a few errors that need to be resolved, a lot of progress has already been made.

Objectives: The main objectives are to retrieve web documents related to specified domains, use natural language processing to analyze and index the content, and provide an interactive interface for users to query the indexed data.

Next Steps: Future work will focus on improving the crawler's efficiency, expanding the system's scalability, and refining the search algorithm to increase the relevance of search results. It would also involve removing the errors for the Configure Indexer Settings. Although this was an optional portion of the project, a lot of progress was made on it even though I never got it to work. So perhaps with extra time and effort, it could be fixed. However, I think that the biggest contribution that could be made is simply getting more comfortable with GitHub and writing Python code outside of Jupyter Notebook, as I have almost no experience with either. This project was very much a trial by fire for me, so with extra time to get more familiar with the software being used, I think a lot more progress could be made.


# Overview
Solution Outline: This project comprises three main components: a web crawler, a data processor, and a search interface. Each component is designed to facilitate maintenance and scalability.

Relevant Literature: The project is inspired by classic IR systems and leverages modern computational methods discussed in CS 429, including techniques for web crawling, data indexing, and query processing.

Proposed System: This system is intended to be deployed as a web service, where users can input queries and receive relevant documents as outputs. It employs machine learning algorithms to enhance search accuracy and uses a web crawler to collect data continuously.
# Design
Intended System Capabilities:
Web Crawling: Customizable and scalable web crawler using Scrapy.
Data Processing: Uses sklearn for efficient data cleaning, processing, and machine learning tasks.
Search Interface: Interactive user interface built with Flask.

Interactions:
Users are supposed to interact with the system via a web interface where they can submit search queries, although this hasn’t been finished yet.
The system is intended to processes these queries using a pre-built index and return the most relevant documents.

Integration:
Integrates Scrapy with Flask to allow real-time data processing and interaction.
Uses sklearn for the application of NLP techniques and to build and refine the search index based on user queries.


# Architecture
Software Components:
Scrapy: For crawling websites and extracting data.
Sklearn: For data analysis and machine learning tasks.
Flask: For building the web interface and handling user requests.

Interfaces:
Web interface built with Flask for users to interact with the system.
RESTful API could be considered for integration into other systems or applications.

Implementation:
The crawler is set up to handle multiple domains with rules specified for scraping.
Data processing scripts are designed to sanitize and prepare text data for indexing.
The search interface utilizes processed data to match user queries with documents.


# Operation
Software Commands:
Installation involves setting up Python 3.10+, along with libraries such as Flask, Scrapy, and sklearn.
Commands for starting the server, initiating crawlers, and installing necessary items via pip install in powershell.

Inputs:
Users are intended to input search queries through the web interface, although this hasn’t been finished yet.
System administrators can input commands for starting/stopping crawlers, updating software, etc.

Installation:
Requires Python 3.10+ installation, along with necessary libraries.
Flask app to run on a standard web server or locally for testing.


# Conclusion
Success/Failure Results:
The system has not been adequately tested.
Limitations include dependency on specific library versions as well as being an unfinished project overall.

Outputs:
With further work, I would try to have search results displayed to the user based on query relevance. However, this hasn’t been properly implemented nor finished yet.

Caveats/Cautions:
Due to a lack of testing, it is hard to trust whether or not the code provided is sufficient. Further testing and debugging is required, but this is definitely a start.

Data Sources:
Links, Downloads, Access Information:
Data is primarily sourced from web pages crawled by the Scrapy component.
Public datasets and APIs could be integrated to the data sources.


# Test Cases
Framework, Harness, Coverage:
Due to a lack of testing, it is hard to trust whether or not the code provided is sufficient. Further testing and debugging is required, but this is definitely a start. However, if I were able to do test cases, then I would do unit tests for each individual component (crawler, processor, UI). I would also do integration tests to ensure that components work together as intended.


# Source Code
Listings, Documentation, Dependencies (Open-Source):
Scrapy for crawling (GPLv2+), sklearn for machine learning tasks (BSD license), Flask for the web interface (BSD license).
A large amount of the initial source code was written using GitHub Copilot. However, a lot of that initial code still had a lot of errors in it and GitHub Copilot didn't always debug the error itself. So debugging the source code was mostly a combination of GitHub Copilot, my own work, and one particular stackoverflow article which has been linked in the bibliography. There are a few errors in my section regarding the Indexer Settings. However, neither I nor GitHub Copilot were able to fix it, and whatever stackoverflow articles I found didn't seem to provide any solution that would permanently fix the issue.


# Bibliography
https://stackoverflow.com/questions/20928769/python-tfidfvectorizer-throwing-empty-vocabulary-perhaps-the-documents-only-c 
