# Dimensionality-reduction-and-Visualization

- We can visualize 2D or 3D data using scatter plots. But what about 4D, 5D or nD, we can use pair plots to do that but upto what extend   we can analyze pair plots, at max we can do that till 6D. Then what after that, here comes Dimensionality reduction.

- Dimensionality reduction is a technique to reduce the nD data to 2D or 3D data where we can visualize the data.
  With more variables, comes more trouble, dimension reduction techniques comes to the rescue.
  
  ## Two components of Dimensionality reduction   
  
  ### 1. Feature selection:
         In this, we try to find a subset of the original set of variables, or features, to get a smaller subset
         which can be used to model the problem. It usually involves three ways:
         
         - Filter
         - Wrapper
         - Embedded
         
  ### 2. Feature extraction:
         This reduces the data in a high dimensional space to a lower dimension space, i.e., a space with lesser
         no. of dimensions.
         
## Advantages of Dimensionality reduction

- Space required to store the data is reduced as the no. of dimensions comes down.

- Less dimensions lead to less computation/training time.

- Some algorithms do not perform well when we have a large dimensions. So reducing these dimensions needs to happen for the algorithm to   be useful.

- It takes care of multicollinearity by removing reduntant features.

- Reducing the dimensions of data to 2D or 3D may allows us to plot and visualize it precisely.

- It is helpful in noise removal also and as a result of that we can improve the performance of models.

## Disadvantages of Dimensionality reduction

- It may lead to some amount of data loss.

- Principal Component Analysis (PCA) tends to find linear correlations between variables, which is sometimes undesirable.

- PCA fails in cases where mean and covariance are not enough to define datasets.

- We may not know how many principal components to keep-in practice, some thumb rules are applied. 

### Common Dimensionality reduction techinques
    1.  Missing Value Ratio
    2.  Low Variance Filter
    3.  Decision Trees
    4.  Random Forest
    5.  High Correlation Filter
    6.  Backward Feature Elimination
    7.  Forward Feature Selection
    8.  Principal Component Analysis (PCA)
    9.  Independent Component Analysis
    10. Factor Analysis
    11. t- Distributed Stochastic Neighbor Embedding (t-SNE)
    12. Uniform Manifold Approximation and Projection (UMAP)

   ![DRT](https://user-images.githubusercontent.com/42858195/60818772-f0a7dd00-a1bb-11e9-97ae-688787f4b918.png)



    
    
