# Traffic-Sign Classification
Developed a traffic-sign recognition pipeline for Driver Assistant Systems on LISA Traffic Sign Dataset [1].
Implemented a three-layered CNN architecture based on [2] which would classify a given traffic-sign into one of the 47 traffic-sign categories with 97.75% accuracy on the test dataset.

Note: This was developed as a part of the traffic sign recognition project done under <a href="http://www.nsit.ac.in/faculty/dee/">Dr. Deepika Kukreja</a>, NSUT.

## About
1. The train.py file consists of the model developed in Keras.
2. The test.py file consists of using the trained model weights to predict on the test data.
3. The test_visualise.py consists of the code used to prepare the demo. The demo takes in an input image and detects the type of road-sign (out of 47 categories).

## References
1. Andreas Møgelmose, Mohan M. Trivedi, and Thomas B. Moeslund, "Vision based Traffic Sign Detection and Analysis for Intelligent Driver Assistance Systems: Perspectives and Survey," IEEE Transactions on Intelligent Transportation Systems, 2012. Available <a href="https://ieeexplore.ieee.org/document/6335478">here</a>.
2. P. Sermanet and Y. Lecun, “Traffic sign recognition with multi-scale convolutional networks,” in 2011 International Joint Conference on
Neural Network, IJCNN 2011, 2011, pp. 2809–2813. Available <a href="http://yann.lecun.com/exdb/publis/pdf/sermanet-ijcnn-11.pdf">here</a>.
