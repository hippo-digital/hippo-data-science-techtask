# Data Science Engineer Technical Test  
This is the repository containing instructions and base data for a technical test for data science 

# Set up

To help us evaluate your response to this test, we would prefer it if you responded using a Jupyter notebook. This allows you to annotate your response as required, and makes your response easier to evaluate.
We'd like you to answer questions, using the language of your choice (Python, SQL)

## Python
If you haven't used Jupyter before, here's how to get yourself set up:

https://jupyter.readthedocs.io/en/latest/install.html#new-to-python-and-jupyter

## SQL

It is possible to answer this test using SQL alone (with some added components). If this is your preference, please ensure your SQL is well annotated.

# Submission

Our preferred response is an annotated Jupyter notebook, please return your code and results to your recruiter.

Please do not return the database via email (it's quite large!).

# The Data

The data used for this test is sourced from the **Museum of Modern Art data on Kaggle**: https://www.kaggle.com/momanyc/museum-collection

## Content

The artworks data set contains 130,262 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in our database. It includes basic metadata for each work, including title, artist, date, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not curator approved.” The artists dataset contains 15,091 records, representing all the artists who have work in MoMA's collection and have been cataloged in our database. It includes basic metadata for each artist, including name, nationality, gender, birth year, and death year.

## The Database

To make sure that this test can run on any machine, we're using SQLite: https://www.sqlite.org/index.html

We have provided an example Python notebook showing how to connect to, and how to query the database using SQL. 

# The Test!

We would like you to approach this as if the Museum of Modern Art is a client and approach the questions as such. The MoMA has approached you for a consulting project and you have been given only this database to work from.
Answer the questions below, providing a narrative and working assumptions:

Answer the questions below, providing a narrative and working assumptions:

### Part 1  
The MoMA is looking to put together some new themed exhibits in the near future. They would like to apply an AI or Data Science driven method of identifying new collections to display.  

* Please review the quality of the data, and present any issues
* Which artist in this data set lived the longest?
* Who are the top 10 artists by the number of artworks?
* Which artist is created the most artwork by total surface area?
* Did any artists have artwork acquired during their lifetime?

### Part 2  
* As a proof of concept, please group the artworks into as many collections as you feel is appropriate, using attributes from both the artist and artworks tables, and assign each artwork to this new group.
* Based on your initial exploration of the artworks, what would you present to the client as your feedback of your chosen methodology? 
* If you were to continue this PoC into the next stage, what direction would you suggest the client takes?

# Good luck!
