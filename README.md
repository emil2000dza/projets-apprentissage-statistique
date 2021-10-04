Two data analysis projects carried out on the occasion of statistical learning courses.

## MNIST Project

This report ("MNIST Report") deals with the study of the representation of handwritten figures acquired on digital tools. For this purpose, the MNIST database is used, which gathers a set of 70,000 examples of each digit, as well as their labels, in order to categorise the representations into different classes. Each image is 28 x 28 pixels, and each pixel is represented by a number (grey level). 
The methods used to distinguish each digit are unsupervised (K-Means, Hierarchy, K-Medoids) and supervised (CNN, MLP) learning methods. 

## Signature Project

This work concerns the study of handwritten signatures acquired on digital tools. For this purpose, the MCYT-100 database is used, which gathers a set of 2500 signatures for 100 individuals (each individual has entered his signature 25 times), in order to categorise the individuals and the signatures in different classes.  The complexity of the 2500 signatures is also integrated in this database and was calculated with the GMM (Gaussian Mixture Model) coupled with the differential entropy measure. The complexity calculation for each signature is available for different numbers of NG Gaussians: 4, 8, 24. 
The signatures are classified according to three complexity categories: low, medium and high complexity. The methods considered are mainly unsupervised learning methods (different configurations for K-Mean and K-Medoid, emphasis on data interpretation (see report).
