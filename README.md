# Latent Factors Collaborative Filtering for Restaurant Recommendation

Reference : 'Matrix Factorization Techniques for Recommender Systems', Yehuda Koren, 2009

*Matrix Factorization with Bias Method*  

Latent factors collaborative filtering by matrix factorization model with bias  
  * Model Description :  
  -Model splits data set (matrix values) into train set and validation set  
  -Model trains two latent factor matrices (user latent factor / item latent factor)   
  -By dot product of two latent factor matrices, model get reconstructed prediction rating matrix  
  -This model can stop early when there is no more train improvement(by checking tolerance)  
  
This CF based recommender system makes personal recommendation for target user based on predicted rating.    

Data from Korea University KOREAPAS sofo

![sofo1](https://user-images.githubusercontent.com/20104945/91419468-65d9e400-e88e-11ea-984e-a5363171cba7.jpg)
![sofo2](https://user-images.githubusercontent.com/20104945/91419473-670b1100-e88e-11ea-81b0-e7168199158d.jpg)

