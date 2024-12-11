# Implementation-of-ML-model-for-image-classification
How it works

  1.The application first loads the pre-trained MobileNetV2 model from TensorFlow's model zoo.
  
  2.The user is prompted to upload an image file (JPG or PNG format).
  
  3.The uploaded image is preprocessed to match the input requirements of the MobileNetV2 model. This involves resizing the image to 224x224 pixels and normalizing the pixel values.
  
  4.The preprocessed image is then fed into the model to obtain predictions.
  
  5.The model's predictions are decoded into human-readable class names and displayed on the screen, along with the confidence scores.

To run the application, use the following command:

    streamlit run app.py
Then, open a web browser and navigate to the URL displayed in the terminal. From the web interface, you can upload an image and see the model's predictions.

Acknowledgements
1.  Streamlit
2.  TensorFlow
