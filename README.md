# Kushagra_Portfolio
Data Science Portfolio of Kushagra Chaturvedi

# [Project 1: Gideon-Chat-bot](https://github.com/Kushagra-Chaturvedi/Gideon-Chat-bot)
Developed a Chatbot and hosted it on Telegram to answer questions of the freshers entering this college. Collected Data about IIT Mandi and different queries a student has while taking admission in a college. Created a Neural Network for training the chatbot. Used text Preprocessing like tokenization and stemming.

# [Project 2: Frosthack_Resyst](https://github.com/Kushagra-Chaturvedi/Frosthack_Resyst)
This is the link of app deployed on Heroku: https://resyst-frosthack.herokuapp.com/
For new account , you must sign up as a service provider. Then Login and provide details about the services you can provide.
For a patient, you don't need an account. Just add the pincode, and all available service providers would shown to you directly.

# [Project 3: Bag-Of-Visual-Words-from-Scratch](https://github.com/Kushagra-Chaturvedi/Bag-Of-Visual-Words-from-Scratch)
Applied Bag Of Visual Words Model on Image Dataset
Applied Bag Of Visual Words algorithm for Image Data from Scratch. It was multi-class Image Data. The Classes were: Botanical Garden, Elevator Shaft and Bus Interior. After implementing the BOVW algorithm, extracted vectors were fed to a multilayer neural network also made from scratch without using any frameworks.
obtained a 32-dimensional representation of each 
image in Training, Validation and Test Data. This 32 dimensional 
representation was feed into the neural network containing 64 neurons in 
Layer 1 and 32 neurons in Layer 2. Both the Layer has sigmoidal 
activation, so does the output layer.
1) Epochs vs Error
<img src="Image_error_epoch.png" alt="Error vs Epochs">
2) Epochs vs Misclassification Count
<img src="Image_misclass_epoch.png" alt="Misclassification vs Epochs">
<br>
No of Epochs:35000<br>
Error on Training: 0.0432<br>
Misclassification count on Training:5<br>
Validation Data:
1) Confusion Matrix:
[[7 2 1]<br>
[3 5 2]<br>
[1 1 8]]<br>
2) Average Accuracy:
0.667<br>
3) Error: 
 0.244<br>
Test Data:<br>
1) Confusion Matrix:<br>
[[35 13 2]<br>
[14 30 6]<br>
[ 4 18 28]]<br>
2) Average Accuracy:
0.62<br>
3) Error:
 0.30

# [Project 4: Movies-Clustering](https://github.com/Kushagra-Chaturvedi/Movies-Clustering)
Clustering Movies based on their Plots
## About:
<p>There are some movies we like, some we don't. Most people have a preference for movies of a similar genre. Some of us love watching action movies, while some of us like watching horror. Some of us like watching movies that have ninjas in them, while some of us like watching superheroes.</p>
<p>Movies within a genre often share common base parameters. Consider the following two movies:</p>
<p><img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="Interstellar" src="https://images-na.ssl-images-amazon.com/images/I/51H4jXmToqL._SX300_BO1,204,203,200_.jpg">
<img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="Gravity" src="https://www.hollywoodreporter.com/wp-content/uploads/2013/08/gravity_2.jpg"></p>
<p>Both movies, <em>Interstellar</em> and <em>Gravity</em>, are movies based on space exploration. Both are marvellous movies and share a good amount of similarity. One could conclude that both of these fall into the same genre of movies based on intuition. In this notebook, I have quantified the similarity of movies based on their plot summaries available on IMDb and Wikipedia, then separate them into groups, also known as clusters. I created a dendrogram to represent how closely the movies are related to each other.</p>

# [Project 5: Fashion_MNIST-End-to-End-Using-Streamlit](https://github.com/Kushagra-Chaturvedi/Fashion_MNIST-End-to-End-Using-Streamlit)
Trained Convolutional Neural Network on Fashion MNIST dataset.
### **Data Description**
This is a dataset of 60,000 28x28 grayscale images of 10 fashion categories,
along with a test set of 10,000 images. 
## **Model Summary**
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
input_8 (InputLayer)         [(None, 28, 28, 1)]       0         
_________________________________________________________________
conv2d_27 (Conv2D)           (None, 28, 28, 32)        320       
_________________________________________________________________
batch_normalization_26 (Batc (None, 28, 28, 32)        128       
_________________________________________________________________
tf.nn.relu_26 (TFOpLambda)   (None, 28, 28, 32)        0         
_________________________________________________________________
max_pooling2d_20 (MaxPooling (None, 14, 14, 32)        0         
_________________________________________________________________
conv2d_28 (Conv2D)           (None, 14, 14, 64)        18496     
_________________________________________________________________
batch_normalization_27 (Batc (None, 14, 14, 64)        256       
_________________________________________________________________
tf.nn.relu_27 (TFOpLambda)   (None, 14, 14, 64)        0         
_________________________________________________________________
max_pooling2d_21 (MaxPooling (None, 7, 7, 64)          0         
_________________________________________________________________
conv2d_29 (Conv2D)           (None, 7, 7, 128)         73856     
_________________________________________________________________
batch_normalization_28 (Batc (None, 7, 7, 128)         512       
_________________________________________________________________
tf.nn.relu_28 (TFOpLambda)   (None, 7, 7, 128)         0         
_________________________________________________________________
max_pooling2d_22 (MaxPooling (None, 3, 3, 128)         0         
_________________________________________________________________
conv2d_30 (Conv2D)           (None, 3, 3, 128)         147584    
_________________________________________________________________
batch_normalization_29 (Batc (None, 3, 3, 128)         512       
_________________________________________________________________
tf.nn.relu_29 (TFOpLambda)   (None, 3, 3, 128)         0         
_________________________________________________________________
flatten_6 (Flatten)          (None, 1152)              0         
_________________________________________________________________
dense_24 (Dense)             (None, 256)               295168    
_________________________________________________________________
dropout_10 (Dropout)         (None, 256)               0         
_________________________________________________________________
dense_25 (Dense)             (None, 128)               32896     
_________________________________________________________________
dropout_11 (Dropout)         (None, 128)               0         
_________________________________________________________________
dense_26 (Dense)             (None, 64)                8256      
_________________________________________________________________
dense_27 (Dense)             (None, 32)                2080      
_________________________________________________________________
dense_28 (Dense)             (None, 10)                330       
<br>
Total params: 580,394<br>
Trainable params: 579,690<br>
Non-trainable params: 704

# [Project 6: OpenCV-Programs](https://github.com/Kushagra-Chaturvedi/OpenCV-Programs)
Developed Motion Detection, Object Tracing and Hand Tracking projects using OpenCV library of Python.
