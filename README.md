# Image-Classification-Using-Deep-Learning-and-Tensorflow

This project introduces you to an image classification task using tensorflow. 5 different dog breeds are classified using a convolutional neural network. Tasks that are included in the project are:

- Use tf.keras.utils.image_dataset_from_directory() method to import image files into a tensordataset and split in a training and test set
- Render images using Pillow library with numpy modifications
- Build a convolutional neural network using keras, layers and Sequential
- Compile and train the model and plot the train and test accuracy using pandas
- Iterate over the model network by adding more layers using maxpooling and dropout regularization to avoid overfitting
- Augment data using image manipulation techniques such as flipping, zooming and rotation
- Rendering images in a pandas dataframe using base64 and io libraries with HTML tags
- Analyze neural network accuracy using accuracy_score and confusion_matrix from sklearn

This project demonstrates some key insights such as overfitting principles, network tuning and image manipulation. The project relies on tensorflow, which in my settings only runs using CPU. To be able to get access to the full benefits of parallellized computation, GPU compatibility would be ideal. Additional improvements would be further network modifications and larger datasets. It would also be interesting to look at the pytorch library instead to compare the performance.
