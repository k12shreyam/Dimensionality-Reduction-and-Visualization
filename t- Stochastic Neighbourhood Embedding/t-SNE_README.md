# What is t-SNE?

 - t-SNE is an unsupervised, non-linear technique primarily used for data exploration and visualizing high-dimensional data.
   In simple, it gives you a feel or intuition of how the data is arranged in a high-dimensional space. 
   
 - It is extensively used/applied in image processing, NLP, genomic data and speech processing.
 
# Why you should learn t-SNE?

 t-SNE prevents the **Crowding problem**, where points tend to get crowded in low-dimensional space due to the curse of dimensionality.
 t-SNE optimizes the embeddings directly using gradient descent. The cost function is non-convex though, meaning there is the risk of
 getting stuck in local minima.<br/>
 In simple, it is incredibly flexible, and can often find structure where other dimensionality reduction algorithms cannot.
 The algorithm makes all sorts of adjustments that tidy up its visualizations. Don’t let the hidden “magic” scare you away from the
 whole technique, though. The good news is that by studying how t-SNE behaves in simple cases, it’s possible to develop an intuition
 for what’s going on.

# What t-SNE is actually doing?

 t-SNE a non-linear dimensionality reduction algorithm finds pattern in the data by identifying observed clusters based on similarity 
 of data points with multiple features.But it is not a clustering algorithm,it is a dimensional reduction algorithm.This is because it
 maps the multi-dimensional data to a lower dimensional space, the input festures are no longer identifiable. Thus, **You cannot make
 any inference based only on the output of the t-SNE**. So, it is mainly for data exploration and visualization technique.
 
# Time and Space Complexity :

 - t- SNE algorithm computes pairwise conditional probabilities and tries to minimize the sum of the difference of the probabilities in
   higher and lower dimensions. This involves a lot of calculations and computations. So the algorithm is quite heavy on the system
   resources.
   
 - t-SNE has a **quadratic time** and space complexity in the number of data points. This makes it particularly slow and resource draining
   while applying it to data sets comprising of more than 10K observations.
   
 # Limitations of t-SNE :
 
  - Non-convexity of optimization
  - Complex manifolds

# Points to be remember in t-SNE:

  - Cluster sizes in a t-SNE plot mean nothing
  - Distances between clusters might not mean anything
  - Random noise doesn’t always look random
  - You can see some shapes, sometimes
  - For topology, you may need more than one plot
