# final_term_project
-----
### About The Project
There are many machine learning tools for classification in scikit learn library. In this project, I find the best model for classification problem. In the process of comparing the accuracy of the models, I finally use Linear Discriminant Anlaysis model which give me the highest accuracy. In the code, there are some explanation of the dataset for face recognition, hyperparameter tuning procedures, and the accuracy of the model.

-----
### Dataset Explanation
I use the Olivetti faces dataset. This dataset contains a set of face images taken between April 1992 and April 1994 at AT&T Laboratories Cambridge. There are ten different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions such as open or closed eyes, smiling or not smiling, and facial details such as waring glasses or not. All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position with tolerance for some side movement. The image is quantized to 256 grey levels and stored as unsigned 8-bit integers; the loader will convert these to floating point values on the interval [0, 1], which are easier to work with for many algorithms. The “target” for this database is an integer from 0 to 39 indicating the identity of the person pictured; however, with only 10 examples per class, this relatively small dataset is more interesting from an unsupervised or semi-supervised perspective. The original dataset consisted of 92 x 112, while the version available here consists of 64x64 images.

-----
### Algorithm Explanation(Linear Discriminant Analysis)
Linear discriminant analysis (LDA), normal discriminant analysis (NDA), or discriminant function analysis is a generalization of Fisher's linear discriminant, a method used in statistics and other fields, **to find a linear combination of features that characterizes or separates two or more classes of objects or events**.

-----
### Hyperparameter Explanation
There are some hyperparamters to tune for the best model. I tune 'solver' which is one of the hyperparameters of the Linear Discriminant Analysis. I use GridSearchCV in sklearn.model_selection to choose the best hyperparameter, and finally choose to use 'svd' for 'solver'. There are other hyperparameters except for the 'solver', however, I could find out that they do not affect the accuracy of the model at all. Therefore, I didn't include them in the code.

    solver : {‘svd’, ‘lsqr’, ‘eigen’}, default=’svd’

    -'svd'  : Singular value decomposition
    
    -'lsqr' : Least squares solution
    
    -'eigen': Igenvalue decomposition

-----
### License
Distributed under the MIT License. See 

    LICENSE.txt
for more information.

-----
### Contact
E-mail : abbeybrian@cau.ac.kr

-----
### Acknowledgements
