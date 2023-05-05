This project is developed based on my first course in Coursera which is titled: "Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning". This project is simply developed for distinguishing between Human and Horse images. It's an opener to perform more complex and specialized works based on Artificial Intelligence, Machine Learning, and Deep Learning in my fields of study and my interests.
For running the project you can simply open it via Colab, then running the first cell; it will automatically download the data set and 

What the project does
    Why the project is useful
    How users can get started with the project
    Where users can get help with your project
    Who maintains and contributes to the project

In this course, we learn how to use TensorFlow to implement a basic Neural Network and finally to basic Convolutional Neural Network


Hi. In this Program, which is based on my Coursera assinment or exresises, a model is developed for distinguishing between Human and Horse images.

    For training the model "Horses or Humans" dataset is used. This contains over a thousand images of horses and humans with varying poses and filesizes. Some of the images are showed to get a better sense of what they look like.
    ImageDataGenerator class is used to prepare the dataset, so it can be fed to a convolutional neural network.
    The model is developed through TensorFlow, and totally 5 Convolution layers are used (The model architecture can be checked via model.summary().
    The model is trained with binary_crossentropy loss and RMSprop optimizer.
    Preprocessing of images is done by ImageDataGenerator; the images are auto-labeled, and they are fed to the model in baches of 128 and size of 300*300
    Training is performed for 15 epochs
    You can check the model by running "Model Prediction" which is prepared at the end of. This code will allow you to choose 1 or more files from your file system, upload them, and run them through the model, giving an indication of whether the object is a horse or a human.

Please Note: Due to several reasons the model might not be accurate enough, however I'm trying to develope the model by various tools. :-)
