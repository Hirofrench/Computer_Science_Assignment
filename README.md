# Computer_Science_Assignment
This code is originally made in google colab, therefore slight adjustments might be needed if it ran on another platform.

In In[5] the data preperation is done to reduce the noise.

In In[7] the model words are extracted from the title and the key-value pairs.

In In[19] the minhashing is done, and the lsh is performed.

Then in In[9], the clustering algorithm starts, first the data is cleaned on different restrictions, such as screenszie and brand

In In[10], TDIF is calculated, this is however not used for the final result.

In In[11] the ngram similarities are calculated

In In[12] the cosine similarity is calculated which is used for the TMWM similarity

In In[14] the parameter grids are displayed

In In[15] the function is displayed which bayesian gridsearch tries to optimize

In In[21] the whole procedure per bootstrap is done

In In[16] the evaluation measures are calculated

The last code block is the 'main', as if you run this it will automatically run the whole proces.
Here you can change the number of bootstraps
