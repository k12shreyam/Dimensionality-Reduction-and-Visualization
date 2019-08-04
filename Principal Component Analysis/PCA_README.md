# What is PCA?
  
  Principal Component Analysis is simplest and fundamental dimensionality reduction method where we used to convert high dimensional dataset
  (say D) to low dimensional dataset (say D') where D'<D preserving approximately 90% of the variance/spread/information available in 
  the dataset.
  
  ![PCA](https://user-images.githubusercontent.com/42858195/62429304-b08c3980-b72a-11e9-9009-b236a3d8f981.png)
  
  The image above shows the transformation of a high dimensional data (3 dimension) to low dimensional data (2 dimension) using PCA.

  
# Why you should learn PCA?

 - As the dimensions of data increases, the dificulty to visualize it and perform computations on it also increases.So, how to reduce 
   the dimensions of a data:
   - Remove the reduntant dimensions
   - Only keep the most important dimensions
   
 - PCA is a dimensionality reduction technique for feature extraction.
 
 - PCA combines our input variables in a specific way,then we can drop the "least important" variables while still retaining the most 
   valuable parts of all of the variables.
   
 - As an added benefit,each of the "new" variables after PCA are all independent of one another.Because of this there will be no correlation.
   This is mostly used for linear models, because linear models assumes that all the variables are independent.
   
 - PCA finds a new set of dimensions such that all the dimensions are orthogonal and ranked according to the variance of the data along them.
   It means more important principle axis occurs first.
   
# When to use PCA?
 
 1. Do you want to reduce the no. of variables ,but aren't able to identify variables to completely remove from consideration?
 
 2. Do you want to ensure your variables are independent of one another?
 
 3. Are you comfortable making your independent variables less interpretable?
 
                         "" If you answered "YES" to all 3 questions, then PCA is a good method to use ""
                                "" If you answered "NO" to question 3, you should NOT use PCA ""
                                
# What do we get from PCA?

 - A measure of how much each variable is associated with one another. (**Covariance Matrix**)
 
 - The directions in which our data are dispersed. (**Eigen Vectors**)
 
 - The relative importance of these different directions. (**Eigen Values**)
 
 - PCA combines our predictors and allows us to drop the eigen vectors that are relatively unimportant.
 
 
# Points to remember about PCA:

 1. PCA is used to overcome features redundancy in a data set.
 2. These features are low dimensional in nature.
 3. These features a.k.a components are a resultant of normalized linear combination of original predictor variables.
 4. These components aim to capture as much information as possible with high explained variance.
 5. The first component has the highest variance followed by second, third and so on.
 6. The components must be uncorrelated.
 7. Normalizing data becomes extremely important when the predictors are measured in different units.
 8. PCA works best on data set having 3 or higher dimensions. Because, with higher dimensions, it becomes increasingly difficult to make
    interpretations from the resultant cloud of data.
 9. PCA is applied on a data set with numeric variables.
10. PCA is a tool which helps to produce better visualizations of high dimensional data.
