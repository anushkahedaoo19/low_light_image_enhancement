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
<br>
Architecture
![img](https://github.com/user-attachments/assets/86f834ba-6ea5-4e51-b955-f992ea29a08e)
<br>
# Output
![WhatsApp Image 2025-12-12 at 13 38 23_fc059ed7](https://github.com/user-attachments/assets/d308bec5-bb71-4123-9ef9-618867eb1b92)

![WhatsApp Image 2025-12-12 at 13 39 14_fc6eea69](https://github.com/user-attachments/assets/b4dec78e-4474-4bcf-9746-4915a1832257)
