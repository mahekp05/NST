# NST
Neural Style Transfer Using TensorFlow Hub

This project demonstrates how to perform Neural Style Transfer (NST) using a pre-trained model from TensorFlow Hub. NST is a deep learning technique that allows you to blend the content of one image with the artistic style of another, creating a stylized image that retains the structure of the content while adopting the style's visual patterns and textures.

How It Works
Import Dependencies: TensorFlow and TensorFlow Hub are used for the style transfer model, while NumPy, OpenCV, and Matplotlib handle image manipulation and visualization.
Load Images: Two images are loaded: a content image and a style image.
Preprocess Images: The images are preprocessed into tensors and resized to match the model's input requirements.
Style Transfer: The TensorFlow Hub model transfers the style from the style image to the content image, producing a stylized output.
Visualize and Save: The stylized image is displayed and saved as generated_img.jpg using OpenCV.

Example
Content Image: FtmKBvYXgAAlWxe.jpeg
Style Image: monet.jpg
Stylized Output: generated_img.jpbg




