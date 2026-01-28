# <img src="https://img.shields.io/badge/Fashion--MNIST--Image--Classification-FF6B6B?style=for-the-badge&logo=tensorflow&logoColor=white" alt="Fashion MNIST Classification"/>

<p align="center">
  <img src="https://img.shields.io/badge/Deep_Learning-orange?style=flat-square" alt="Deep Learning"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
</p>

---

### 🔗 **Google Colab Link:**
[![Open In Colab](https://img.shields.io/badge/Open_in_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/1fDL74MtsRF74g4T3GMDY9Pkj5BewyXZ8?usp=sharing)

---

## 📋 Questions:

### ![1](https://img.shields.io/badge/1-4A90E2?style=flat) What is the Fashion MNIST dataset?
Fashion MNIST is a dataset of 70,000 grayscale images showing clothing items like shirts, shoes, and bags, split into 10 different categories.
It's basically a more challenging replacement for the classic MNIST handwritten digits dataset that people use to train and test machine learning models.

### ![2](https://img.shields.io/badge/2-4A90E2?style=flat) Why do we normalize image pixel values before training?
We normalize image pixel values to make training easier and faster for the neural network. By converting the original pixel values which range from 0 to 255 
into smaller numbers like 0 to 1, the model can learn patterns more smoothly without getting confused by large numbers that might slow down or mess up the learning process.

### ![3](https://img.shields.io/badge/3-4A90E2?style=flat) List the layers used in the neural network and their functions.
**Flatten Layer** - Takes the 2D image and reshapes it into a flat list of numbers.

**Dense/Hidden Layer** - This is where the actual learning happens, with neurons detecting patterns in the clothing images.

**Output Layer** - Makes the final prediction about what type of clothing item it is, choosing from 10 possible categories.

### ![4](https://img.shields.io/badge/4-4A90E2?style=flat) What does an epoch mean in model training?
An epoch is one complete pass through the entire training dataset. So if you train for 10 epochs,
the model sees and learns from every single training image 10 times, adjusting its weights each time to get better at making predictions.

### ![5](https://img.shields.io/badge/5-4A90E2?style=flat) Compare the predicted label and actual label for the first test image.
Both the predicted and actual labels were **9**. The model got it right! ✅ This shows the network correctly identified the first test image.

### ![6](https://img.shields.io/badge/6-4A90E2?style=flat) What could be done to improve the model's accuracy?
To improve the model's accuracy, we could use a **CNN** instead of dense layers since CNNs are better at recognizing image patterns.
We could also add more layers or neurons, train for more epochs, use dropout to prevent overfitting, or try data augmentation like rotating and flipping images.

---

<p align="center">Made with ❤️ for Deep Learning</p>
