# FrogSoundGuard-Frog-Sound-Identification-for-Pet-Protection-TinyMl-
In this project, we explore the implementation of a sound classification system using TinyML techniques on an embedded platform. The goal was to develop a lightweight and efficient neural network capable of distinguishing between frog vocalizations and ambient sounds. The system was developed using the Arduino Nano 33 BLE Sense board, a low-power microcontroller with integrated sensors and support for machine learning applications.

For model training, two datasets were used: the Anuran Sound Dataset, which contains recordings of frog vocalizations, and the Noise Audio Dataset, composed of various environmental sounds. The data were processed to standardize the sampling rate at 16 kHz, ensuring compatibility with the embedded audio processing pipeline. Signal features were extracted using the Mel Frequency Energy (MFE) method, suitable for representing relevant information in acoustic recognition tasks.

Model training and deployment were performed on the Edge Impulse platform, enabling real-time implementation on devices with limited computational resources. The motivation behind the project relates to the presence of poisonous frog species in certain regions, whose vocalizations may pose a risk to domestic animals, especially dogs, which are at risk of poisoning upon contact with these frogs.

This project aims to mitigate this risk by identifying anuran sounds in real time, using an embedded machine learning model on low-power microcontrollers. Based on the publicly available Anuran Sound Dataset (Kaggle), the objective is to train a sound classification model capable of identifying characteristic frog vocalizations, focusing on species found in Brazil or those with similar vocalizations. Since the base dataset contains only three species found in Brazil, the team is considering expanding the scope to include sounds of other common rural animals such as chickens, pigs, crickets, among others. This expansion aims not only to improve model accuracy but also to enhance its generalization capability, allowing it to differentiate sounds unrelated to frogs, thus reducing false positives and providing more reliable alerts.

#Project Access
The complete project can be accessed on Edge Impulse Studio at the following link:
https://studio.edgeimpulse.com/public/732300/live

#Data Acquisition and Processing
The data acquisition and processing workflow can be accessed through the following link:
[Google Colab Notebook](https://colab.research.google.com/drive/1xhx4RFAM15ddUKf0M4hm1jB-SXeeMCul?usp=sharing)

#Public Datasets Used
For this project, two public datasets available on Kaggle were used:

##Anuran Sound (Frogs or Toads):
https://www.kaggle.com/datasets/mehmetbayin/anuran-sound-frogs-or-toads-dataset/data

##Noise Audio Data (ESC-50):
https://www.kaggle.com/datasets/javohirtoshqorgonov/noise-audio-data

