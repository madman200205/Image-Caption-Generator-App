Image Caption Generator App:

This is a Streamlit app that generates captions for images using the ViT-GPT2 image captioning model.


Requirements

The following packages are required to run this app:

streamlit

transformers

torch

PIL


You can install them using the following command:

pip install streamlit transformers torch Pillow


Usage

To run the app, open a terminal in the directory where app.py is located and run the following command:

streamlit run app.py

After that, the app will open in your browser. Upload an image and enter the number of captions to generate, and the app will generate captions for the uploaded image.

About the model

The ViT-GPT2 model is a combination of the Vision Transformer (ViT) and the GPT-2 language model. The ViT-GPT2 model is capable of generating captions for images by first encoding the image using the ViT and then generating text using the GPT-2 language model.

Author

This app was created by Madan S.
