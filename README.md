This project is developed based on my first course in Coursera which is titled: "Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning". This project is simply developed for distinguishing between Human and Horse images. It's an opener to perform more complex and specialized works based on Artificial Intelligence, Machine Learning, and Deep Learning in my fields of study and my interests.
For running the project, you can simply open it via Colab, then running the first cell; it will automatically download the dataset, auto-label them, and finally after pre-processing of images they will be fed into the model and training is performed. (Note: Some of the details related to this program are listed below).
You can check the model by running "Model Prediction" which is prepared at the end of program. This code will allow you to choose one or more files from your file system, upload them, and run them through the model, giving an indication of whether the object is a horse or a human. please note that as this project is simply designed with low number of training images, it is not always correct.

For training the model "Horses or Humans" dataset is used. This contains over a thousand images of horses and humans with varying poses and filesizes. Some of the images are showed to get a better sense of what they look like.
ImageDataGenerator class is used to prepare the dataset, so it can be fed to a convolutional neural network.
The model is developed through TensorFlow, and totally 5 Convolution layers are used (The model architecture can be checked via model.summary().
The model is trained with binary_crossentropy loss and RMSprop optimizer.
Preprocessing of images is done by ImageDataGenerator; the images are auto-labeled, and they are fed to the model in baches of 128 and size of 300*300
Training is performed for 15 epochs
