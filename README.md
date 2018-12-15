# ECE285_Final

Description
===================
In this project, we achieve classification of dog breeds from Stanford Dog Dataset which contains images of 120 dog breeds. DenseNet, VGG19 and InceptionV3 were used to extract the features. To get a better accuracy, we apply transfer learning on different networks such as VGG19 and InceptionV3. These networks were already built on Keras, which is a deep learning library and provides some popular neural networks. The result of this project can be used in identification of dogs in images.

Requirements
===================
TensorFlow    version: 1.12.0

Keras         version: 2.1.6-tf

Run Time
===================
./launch-tf-gpu.sh 
or
./launch-pytorch.sh

Code Organization
===================

src/Demo.ipynb                    -- Run a demo of our code

src/evaluate_naive.ipynb          -- Run the naive conditions of inceptionv3, VGG and Densenet121

src/inceptionv3.ipynb             -- Train and fine tune the inceptionV3 model and evaluate its performance

src/main.ipynb                    -- compare the performance of different loss functino and use the most proper one

src/prep.ipynb                    -- prep for the data

src/VGG.ipynb                     -- Train and fine tune the VGG model and evaluate its performance

src/Densenet121.ipynb             -- Train and fine tune the Densenet121 model and evaluate its performance

Data set
===================
Stanford_Dog_Breed
