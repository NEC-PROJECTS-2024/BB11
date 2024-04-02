BB-11

Taffic-Sign-Recognition using Deep Learning

Team Details:

1. Naru Sumanth Reddy
2. Bathula Praveen

Introduction:

The automatic recognition of traffic signs is essential to autonomous driving, assisted driving, and driving safety. Currently, convolutional neural network (CNN) is the most popular deep learning algorithm in traffic sign recognition. However, the CNN cannot capture the poses, perspectives, and directions of the image, nor accurately recognize traffic signs from different perspectives. To solve the problem, the authors presented an automatic recognition algorithm for traffic signs
based on visual inspection. Furthermore, a traffic sign recognition learning architecture was created based on CapsNet, which relies on neurons to represent target parameters like dynamic routing, path pose and direction, and effectively capture the traffic sign information from different angles or directions. Finally, our model was compared with several baseline methods through experiments on LISA (Laboratory for Intelligent and Safe Automobiles) traffic sign dataset. The model performance was measured by mean average precision (MAP), time, memory, floating point operations per second (FLOPS), and parameter number. The results show that our model consumed shorter time yet better recognition performance than baseline methods, including CNN, support vector machine (SVM), and region-based fully convolutional network (R-FCN) ResNet 101.

DataSet:

Link :- https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

Deployment:

Link :- http://34.207.91.20:5000/