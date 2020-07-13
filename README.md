# Gender-Detection
The main objective of our project is to classify the human face wheather it is male or female.It does so by using Convolution Neural
Networks. We used the datasets of more than 4000 images which is available at http://www.milbo.org/muct. 
The facial structure of male and female are quite different which we are instinctivly good at differentiating. For a computer to recognize
those traits, lots of training data are required. The difference revealed so far are https://www.palmbeachplastics.com/facial-feminization-surgery-ffs/7-features-of-a-feminine-face/ . We used Keras libraries which provides all libraries required to create CNN model. In that we used Sequential model. Different architecture 
were tested. Among which the architecture with 3 hidden layers, having 128,128,128 nodes respectively. The input layer takes 64 inputs.
The size of the image feed to the network is 64*64*3. We trained the model for 100 epoches. The data were tested which gave us the accuracy
of 85.5%. 
The trained model is present here.
The codes are in jupiter notebook.
# gender-detection
