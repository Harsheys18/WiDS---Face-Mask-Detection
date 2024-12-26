# FRAMEWORK

In this course, you'll learn how to use TensorFlow, powerful tool for data science and machine learning. Starting with creating tensors and performing operations on them, you'll quickly move to building and deploying deep learning models. You'll construct neural networks from scratch, utilize Convolutional Neural Networks (CNNs) for tasks like image recognition, and apply regularization techniques such as L2 and Dropout to improve model performance. The course also includes tutorials on saving and loading models, ensuring your work is reusable and accessible. By the end, you'll be well-equipped to handle various data science and machine learning projects.

## Tensorflow

> [!Tip]
> All the videos can be watched at **1.5x speed**  
> USE NOTEBOOK [**COLAB**/JUPYTER]

1. <span style="font-size:18px">**[Install and Setup](https://youtu.be/5Ym-dOS9ssA?si=lpQeaEaSqo9jOtvi)**</span>  
   `pip3 install tensorflow` (if using on local notebook/editor)  
   Setup isn’t required for working in colab

2. <span style="font-size:18px">**[Tensorflow Basics](https://youtu.be/HPjBY1H-U4U?si=xTni0ae-S0vgbQVA)**</span>  
   TensorFlow basics encompass creating tensors using constants or variables, performing operations such as element-wise and matrix multiplication, reshaping tensors, computing dot products, applying broadcasting, and utilizing activation functions for neural network training and inference.  
   _You can skip os.environ[...] = ‘2'_

3. **[Neural Network](https://youtu.be/pAhPiF3yiXI?si=jodY8SIy5PUapbzo)**  
   Neural networks consist of interconnected neurons arranged in layers, processing input data through weights and activation functions to make predictions.

4. **[Regularization](https://youtu.be/kJSUq1PLmWg?si=yfzLDoywCIZ3zE92)**  
   Regularization techniques in neural networks prevent overfitting by adding constraints or penalties, such as L1/L2 regularization or dropout, to the model's training process.

5. **[Model Subclassing](https://youtu.be/WcZ_1IAH_nM?si=iftvnOL3IBpq-qYp)** (OPTIONAL)  
   TensorFlow's model subclassing allows custom model architectures by subclassing `tf.keras.Model`, enabling flexibility in defining layers, forward pass, and custom training loops for complex neural network designs.

6. <span style="font-size:18px">**[Model Saving and Loading](https://youtu.be/idus3KO6Wic?si=SFuwbX3sZWX6CEsv)**</span>  
   Model saving and loading in neural networks involve storing trained model parameters to disk and reloading them for inference or further training, using formats like HDF5.

7. <span style="font-size:18px">**[Custom Dataset for Images](https://youtu.be/q7ZuZ8ZOErE?si=Xu9uxKgzL9oYQvIa)**</span>  
   Creating a custom dataset of images is necessary for training neural networks on specific tasks or domains not covered by existing datasets, ensuring better model performance and accuracy.

**EXPLORE THE [TENSORFLOW OFFICIAL DOCUMENTATION](https://www.tensorflow.org/api_docs/python/tf/keras) FOR MORE**
