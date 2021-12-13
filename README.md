# final_term_project
-----
### Brief explanation of the project
There are many machine learning tools for classification in scikit learn library. In this project, I found the best model for classification problem. In the process of comparing the accuracy of the models, I finally used Linear Discriminant Anlaysis model which gave me the highest accuracy. In the code, there are some explanation of the dataset for face recognition, hyperparameter tuning procedures, and the accuracy of the model.

-----
### Dataset explanation
I used the Olivetti faces dataset. 
we will use the Olivetti faces dataset. This dataset contains a set of face 
images taken between April 1992 and April 1994 at AT&T Laboratories Cambridge. The 
sklearn.datasets.fetch_olivetti_faces function is the data fetching, caching function that downloads the 
data archive from AT&T. There are ten different images of each of 40 distinct subjects. For some 
subjects, the images were taken at different times, varying the lighting, facial expressions such as open 
or closed eyes, smiling or not smiling, and facial details such as waring glasses or not. All the images 
were taken against a dark homogeneous background with the subjects in an upright, frontal position 
with tolerance for some side movement. The image is quantized to 256 grey levels and stored as unsigned 8-bit integers; the loader will 
convert these to floating point values on the interval [0, 1], which are easier to work with for many 
algorithms. The “target” for this database is an integer from 0 to 39 indicating the identity of the 
person pictured; however, with only 10 examples per class, this relatively small dataset is more 
interesting from an unsupervised or semi-supervised perspective. The original dataset consisted of 92 
x 112, while the version available here consists of 64x64 images
