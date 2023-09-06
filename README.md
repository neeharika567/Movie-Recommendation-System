# Movie Recommendation System

 A Recommendation System is a tool designed to predict/filter the items as per the user’s behavior.

 ## About Recommendation Systems
 Amazon, one the the most famous companies around the world has spent over 10 years in developing a recommender system for their needs. As a result, the additional sales were about another 20% from recommendations in 2002.Moreover, Netflix established a competition in 2009 to improve the accuracy of its movie recommender system by 10%, indicating how much important a recommender system can be for the success of a company. Already, 35 percent of what consumers purchase on Amazon and more than a half of what they watch on Netflix come from recommendations systems.

Recommender systems can significantly enhance user likelihood to buy the items recommended to them, the loyalty and their overall satisfaction.They reduce transaction costs of finding and selecting items in an online shopping environment.Since they serve to reduce consumer search costs and uncertainty associated with the purchase of unfamiliar products, recommendation systems offer an improvement regarding decision making process and quality. Recommender systems can significantly improve a company’s revenue as they play a key role in cross selling. They make it possible for companies to ensure that the customer regularly discovers new products that may be of interest to him. The ideal situation is one where your existing customer is not aware of a product or service that would improve their customer experience. From this point of view, it is very likely that clients will return to the provider and recommend it to others.


## About My Project
My project is a *Content Based* Recommendation System that tailor recommendations to users by analyzing the past preferences of the user and mapping it to similar content movies. By examining features such as genre, director, theme, and other descriptive elements, this project suggests movies guiding users in choosing their next watch, thus enhancing user experience.

## Dataset
The dataset *movies.csv* contains 4809 movies represented in each row and their 24 features represented in each column. I have focused my project on the features, 'genres','keywords','cast','tagline' snd 'director'.

## Cosine Similarity
Cosine similarity is a metric used to measure the similarity of two vectors. Specifically, it measures the similarity in the direction or orientation of the vectors ignoring differences in their magnitude or scale. Both vectors need to be part of the same inner product space, meaning they must produce a scalar through inner product multiplication. The similarity of two vectors is measured by the cosine of the angle between them.

In cosine similarity, data objects in a dataset are treated as a vector. To convert the features that are originally in text form to vectors , I have used the *Tf-idf Vectorizer*. *Tf* stands for *Term Frequency* which is tf the number of times a term appears in a particular statement. *idf* stands for *Inverse Document Frequency* which is a measure of how common or rare a term is across the entire corpus of statements. If the word is common and appears in many statements, the idf value (normalized) will approach 0 or else approach 1 if it’s rare.

![pic](https://storage.googleapis.com/lds-media/images/cosine-similarity-vectors.original.jpg)

## Input and Output
I ask the user for a movie name, they want to have recommendations of.

![pic](https://github.com/neeharika567/Movie-Recommendation-System/blob/main/ask_name.PNG)

![pic]()
![pic]()
![pic]()

 
