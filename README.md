# Choose your vogue
The objective of the project is to build a system to recommend fashion options based on the user's input using deep learning and transfer learning techniques.

# Dataset details
The data used for this project is a subset of Visuelle 2.0. Visuelle 2.0 is a dataset containing real data for 5355 clothing products of the retail fast-fashion Italian company, Nuna Lie. Specifically, Visuelle 2.0 provides data from 6 fashion seasons (partitioned in Autumn-Winter and Spring-Summer) from 2017-2019, right before the Covid-19 pandemic. 

# Methods
ResNet-50 is a convolutional neural network that is 50 layers deep.A Residual Neural Network (ResNet) is an Artificial Neural Network (ANN) of a kind that stacks residual blocks on top of each other to form a network. Keras is a deep learning API that is popular due to the simplicity of building models using it. Keras comes with several pre-trained models, including Resnet50. A pretrained version of the network trained on more than a million images from the ImageNet database was imported. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. The network has an image input size of 224-by-224. ResNet enables effective feature extraction for accurate recommendation of fashion products.

# Model architecture
The ResNet-50 model consists of 5 stages each with a convolution and Identity block. Each convolution block has 3 convolution layers and each identity block also has 3 convolution layers. The ResNet-50 has over 23 million trainable parameters. The architecture is as shown below.
<img width="559" alt="image" src="https://user-images.githubusercontent.com/98405826/202853577-1667047b-7edd-4c4f-b269-1e5b02d6da81.png">

# UI development
The user interface for this project was built with the help of streamlit. Streamlit is an open source app framework in Python language. It helps us create web apps for data science and machine learning in a short time. It is compatible with major Python libraries such as scikit-learn, Keras, PyTorch, SymPy(latex), NumPy, pandas, Matplotlib etc.

# Installation
To run this code in your local system you have to download this repository using-
git clone 
