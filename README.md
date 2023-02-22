# NoSQL-challenge
Submission for Challenge 12 - NoSQL using mongoDB

## Summary of Analysis

Analysis is being conducted to evaluate some of the ratings data in order to help the journalists of food magazine, *Eat Safe, Love,* and food critics decide where to focus future articles. The analysis is done on behalf of the UK Food Standards Agency, over data on establishments across the United Kindom.

The code is commented in the Jupyter notebooks.

The notebook "NoSQL_setup.ipynb" set up the data for analysis using as a source the database "uk_food" and collection "establishment" - contained in the file "establishments.json" in the Resources folder.

The notebook "NoSQL_analysis.ipynb" use the data from establishment. 

The analysis answers the following questions:
- Which establishments have a hygiene score equal to 20
- Which establishments in London have a RatingValue greater than or equal to 4
- What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant "Penang Flavours"
- How many establishments in each Local Authority area have a hygiene score of 0
