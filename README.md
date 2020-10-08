# Recommender-Systems

Recommender Systems are crucial to any Organization. It also helps customer to discover new and relevant products.

# About Dataset

Dataset contains 9742 different movies and nearly 100k ratings.

# Type of Recommendations

<ol>
<li>
Popularity Based Recommendation </li><li>
Content Based Recommendation </li><li>
Item Based Collaborative Filtering </li><li>
User Based Collaborative Filtering </li><li>
Matrix Factorization </li></ol>

# How Recommendation Works

1. Popularity Based Recommendation Engine recommends movies which are very popular. It depends on number of views and number of likes.

2. Content Based Recommendation Engine recommends movies based on content type. For example, If you watch action movie then you get recommended other popular action movies. 

3. Item Based Collaborative Filtering recommends movies based on item similarity. For instance, If you watch one part of Harry Potter then you get recommended other parts since these movies are similar in nature. Another example, If you buy a laptop on amazon, you get recommended Laptop Bag. Since these two items were bought together mostly.

4. User Based Collaborative Filtering recommends movies based on user similarity. For example, You watched 10 different movies and rated them. Now there is this other person Steve who watched same movies and also rated them same as you have. Then let's say this Steve watches another movie and gives it five star rating which means he likes the movie so that movie gets recommended to you no matter the content type. Since you both are similar in nature so if Steve likes it then you may like it too.

5. Matrix Factorization is really a complex method to explain. In simple words, It captures the latent features between movies and users, then estimates how would you react to particular content. Based on that it recommends content to you.


</br></br></br>

<b>1) In popularity based system, I have consider minimum total count of rating and average rating.</b></br></br></br>
![alt text](https://github.com/Jenil245/Recommender-Systems/blob/master/top_10.PNG)
</br></br>
<b>
2)For content based, there are two ways where one depends on cosine similarity and another on sigmoid kernel.
</b></br></br></br>
Cosine Similarity

![alt text](https://github.com/Jenil245/Recommender-Systems/blob/master/content_based_cosine.PNG)
</br></br></br>
Sigmoid Kernel

![alt text](https://github.com/Jenil245/Recommender-Systems/blob/master/content_based_sigmoid.PNG)
</br></br></br>
<b>3)ITEM_BASED COLLABORATIVE FILTERING</b>
</br></br></br>
![alt text](https://github.com/Jenil245/Recommender-Systems/blob/master/itembased_collaborative.PNG)
</br></br></br>
<b>4)USER_BASED COLLABORATIVE FILTERING</b>

</br></br></br>
![alt text](https://github.com/Jenil245/Recommender-Systems/blob/master/userbased_collaborative.PNG)
</br></br></br>

<b>5)MATRIX FACTORIZATION</b>
</br></br></br>
![alt text](https://github.com/Jenil245/Recommender-Systems/blob/master/matrix_factorization.PNG)

</br></br></br>

</br></br></br>
<b>In real world most of the companies use hybrid recommender systems.</b>
