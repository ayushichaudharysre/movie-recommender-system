
![image](https://github.com/ayushichaudharysre/movie-recommender-system/assets/170225137/7c575074-379e-43d9-8bff-330faf1a7990)


In this project I have built a content based movie recommender system. The algorithm recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from the data we have about the items as well as the user’s past preferences.


What it does :
![image](https://github.com/ayushichaudharysre/movie-recommender-system/assets/170225137/b8bd00be-b41e-4eb1-a524-cba7138049d0)









How it does :
![image](https://github.com/ayushichaudharysre/movie-recommender-system/assets/170225137/62679ed6-b0b6-4017-addb-bd94cda61ba7)

Content Based Filtering - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.


How to get the API key for images? :
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

![image](https://github.com/ayushichaudharysre/movie-recommender-system/assets/170225137/989c0c90-6145-41a6-8fd3-b375215a1903)



Similarity Score :
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
![image](https://github.com/ayushichaudharysre/movie-recommender-system/assets/170225137/78af65ca-3507-4008-8294-c111203e74fc)




How Cosine Similarity works? :
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
![image](https://github.com/ayushichaudharysre/movie-recommender-system/assets/170225137/3115597b-df2e-4fce-a5c7-c4c3eab0f9ec)




Sources of the datasets :
I have used the TMDB 5000 movies dataset to build the model

You can collect dataset from https://www.kaggle.com/tmdb/tmdb-movie-metadata

