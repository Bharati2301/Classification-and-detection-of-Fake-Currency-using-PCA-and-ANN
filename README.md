# Classification-and-detection-of-Fake-Currency-using-PCA-and-ANN

## DATA COLLECTION
I gathered a number of images of currently valid old and new banknotes in various denominations. Because just the front side of the notes is usually used for identification, I only photographed the front side. To assess the correctness of my model, I built two sets: Train and Test.

## WHAT TO DO?
* After performing the necessary pre-processing steps, an Artificial Neural Network model was created, but the accuracy was quite low. One possible reason for this could be that all of the notes look similar and have slight variations, so the features can be correlated. As a result, we apply PCA to get separate, non-correlated components.

* When the results of NN with and without PCA were compare, we can plainly observe that accuracy is significantly greater and loss is reduced with PCA. In addition, NN takes much less time using PCA. In a nutshell, PCA is particularly effective for speeding up computations by decreasing data dimensionality. Plus, when you have a lot of dimensionality and a lot of linked variables, PCA can help you increase the accuracy of your classification model.

* Accuracy = 90%

* PCA was also used to capture some of teh variations between real and fake currency, using Eigen Face, which can be used on a large scale to differentiate real and fake currency.

 
 <p align="center">
  <img src="https://img.etimg.com/photo/msid-55510584,quality-100/.jpg" width="550" height="500"/>
</p>
 
 ## REAL LIFE APPLICATION
* While it is still standard practise in daily life to conduct transactions with actual money by handling and counting notes by hand, automated equipment such as ATMs and banknote counters are required for large-scale and secure transactions. 
* We can also have automated ticket selling machines at metro and railway stations that we may use while travelling. This can be widely applied in those systems, but there is always the risk of fraud because there is no human interaction. 
* Fake cash is one of the most common forms of fraud. As humans, we can tell the difference between genuine and counterfeit money, but how should a machine do so? As a result, we used PCA to capture the differences between the genuine and false images.
