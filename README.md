# Books-Recommendation-Engine

I am an avid reader and enjoy quite a few genres of books. Most of my reading options come from the internet or from a friend and after a point the list gets repetitive. When given the task of building a Recommendation Engine I had to choose to make one based on Book Recommendations. For this System I have used the KNN models, popular EDA techniques to analyse the data we have in hand and Vectorises models to identify context and recommend similar books to the users.

In the analysis process, we are first identifying the average rating for each book that has been reviewed multiple times but various popular sources like Google and GoodReads. Doing this will help us in removing the duplicate from the dataset thus reducing redundancy when processing data and ensuring efficient use of time and space. 

The Vectoriser model is more accurate in the recommendations of similar books than the KNN model. The CountVectoriser and TFID Vectoriser model identifies the books similar to the book title input given by the user and responds back with a minimum of 5 recommendations that are in the same genre. The books that are not as popular in content in th3e dataset the model recommends slightly less similar books which still have pretty high accuracy for the model.

### Finding the Output from the Model

**Procedure**
- The user will input the title of the book they liked and would like similar book recommendations.
- The model will search for the books that match the similarities of this book title input from the user.
- The book recommendations will be displayed as output

#### Dataset: Book-Crossing: User review rating Dataset from Kaggle
https://www.kaggle.com/ruchi798/bookcrossing-dataset

The dataset contains three parts- Book details, User Details and the books' rating details
On cleaning and preprocessing the datasets and combining the necessary information from these three into a single dataset we obtain viable information on the book titles, author, publishing, ratings and the ISBN of the book. Using this information we can develop a pretty detailed Book Recommendation Engine.

![alt text](C:\Users\harsh\Pictures\Camera Roll\download4.png)
![alt text] (C:\Users\harsh\Pictures\Camera Roll\download2.png)
![alt text] (C:\Users\harsh\Pictures\Camera Roll\download3.png)
![alt text] (C:\Users\harsh\Pictures\Camera Roll\download1.png)


Inspiration, code snippets, etc.
* [Book-Recommendation-System](https://www.kaggle.com/sercanyesiloz/book-recommendation-system)
* [Recommender-System-for-Books](https://www.kaggle.com/renehlavova/recommender-system-for-books)
* [Collaborative-Book-Recommendation-System](https://www.kaggle.com/sankha1998/collaborative-book-recommendation-system)
