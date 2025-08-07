# low_light_image_enhancement
This project focuses on enhancing images captured in low-light conditions using a deep learning-based approach. We combine the strengths of LeNet for feature extraction and U-Net for image-to-image translation, resulting in a powerful model that improves image brightness, clarity, and detail without introducing artifacts.

**Features**
LeNet is used for learning essential features from low-light images.
U-Net architecture is employed for enhancing image quality through pixel-level restoration.
The model is trained on paired datasets of low-light and normal-light images.

**Dataset Used**<br>
We used the LOL (Low-Light) Dataset, which contains paired low-light and normal-light images.
This dataset helps the model learn to map low-light inputs to well-lit outputs.
https://www.kaggle.com/datasets/soumikrakshit/lol-dataset

**Model Architecture**
-LeNet is used as the encoder to extract features from low-light images.
-U-Net acts as a decoder to reconstruct enhanced images with fine details.

**Technologies Used**

1)Python
2)TensorFlow / Keras
3)OpenCV
4)NumPy, Matplotlib

