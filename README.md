# Two_Collaborative_Filtering_Method_for_Recommender_System

Both Methods are based on latent factor collaborative filtering

1. *Deep Learning Method*  
Latent factors collaborative filtering by Deep Learning model  
  * Model Description :  
  -Two embedding layers create users' latent factors matrix / itmes(restaurants)' latent factors matrix respectively.  
  -Merge layer does dot product of two latent factors matrix, and returns predicted rating matrix.


2. *Matrix Factorization with Bias Method*
Latent factors collaborative filtering by matrix factorization model with bias  
  * Model Description :  
  -Model trains two latent factor matrices (user latent factor / item latent factor)   
  -By dot product of two latent factor matrices, model get reconstructed prediction rating matrix
  





By using above two models, recommender system makes personal recommendation for target user based on predicted rating.    

Data from Korea University KOREAPAS sofo

![sofo1](https://user-images.githubusercontent.com/20104945/91419468-65d9e400-e88e-11ea-984e-a5363171cba7.jpg)
![sofo2](https://user-images.githubusercontent.com/20104945/91419473-670b1100-e88e-11ea-81b0-e7168199158d.jpg)

