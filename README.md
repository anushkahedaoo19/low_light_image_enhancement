# low_light_image_enhancement 
This project focuses on enhancing images captured in low-light conditions using a deep learning-based approach. We combine the strengths of LeNet for feature extraction and U-Net for image-to-image translation, resulting in a powerful model that improves image brightness, clarity, and detail without introducing artifacts.

**Features**<br>
LeNet is used for learning essential features from low-light images.<br>
U-Net architecture is employed for enhancing image quality through pixel-level restoration.<br>
The model is trained on paired datasets of low-light and normal-light images.<br>

**Dataset Used**<br>
We used the LOL (Low-Light) Dataset, which contains paired low-light and normal-light images.<br>
This dataset helps the model learn to map low-light inputs to well-lit outputs.<br>
https://www.kaggle.com/datasets/soumikrakshit/lol-dataset<br>

**Model Architecture**<br>
-LeNet is used as the encoder to extract features from low-light images.<br>
-U-Net acts as a decoder to reconstruct enhanced images with fine details.<br>

**Technologies Used**<br>
<br>
1)Python<br>
2)TensorFlow / Keras<br>
3)OpenCV<br>
4)NumPy, Matplotlib<br>

