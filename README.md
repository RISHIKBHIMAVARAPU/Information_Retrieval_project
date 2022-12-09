------------------------------
project title:
------------------------------
Search Engine for Movies

------------------------------
problem statement:
----------------------------

we need to build a search engine for the movies . Here when user give query we will  display the top 10 most revelant docs to user query.

**About the project**

Dataset used - [Kaggle-movie-plots](https://www.kaggle.com/jrobischon/wikipedia-movie-plots)

1.we used bm25 for indexing (in this we consider the length of doc also)
2.we used cosine similarity for calculating top 10 relevant docs 
3.we implemented filter using the titile of the docs

**code excecution part**
-------------------------------------------------------------------------------------
1. Run files in the order: 

              python3 preprocess.py
              python3 tfidf.py
              python3 server.py
2. In your browser go to `http://localhost:3000/`
3. Type your query in the search bar and wait till it returns the relevant documents 



