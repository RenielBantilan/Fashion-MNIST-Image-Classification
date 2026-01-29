<div align="center">

# 🎨 Fashion MNIST Image Classification

<img src="https://img.shields.io/badge/Deep_Learning-orange?style=for-the-badge" alt="Deep Learning"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>

</div>

---

<div align="center">

### 🚀 **Quick Start**

[![Open In Colab](https://img.shields.io/badge/Open_in_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/1fDL74MtsRF74g4T3GMDY9Pkj5BewyXZ8?usp=sharing)

</div>

---

## 💡 Frequently Asked Questions

<br>

> ### <img src="https://img.shields.io/badge/Q1-4A90E2?style=flat-square" alt="1"/> What is the Fashion MNIST dataset?

Fashion MNIST is a dataset of 70,000 grayscale images showing clothing items like shirts, shoes, and bags, split into 10 different categories.
It's basically a more challenging replacement for the classic MNIST handwritten digits dataset that people use to train and test machine learning models.

<br>

> ### <img src="https://img.shields.io/badge/Q2-4A90E2?style=flat-square" alt="2"/> Why do we normalize image pixel values before training?

We normalize image pixel values to make training easier and faster for the neural network. By converting the original pixel values which range from 0 to 255 
into smaller numbers like 0 to 1, the model can learn patterns more smoothly without getting confused by large numbers that might slow down or mess up the learning process.

<br>

> ### <img src="https://img.shields.io/badge/Q3-4A90E2?style=flat-square" alt="3"/> List the layers used in the neural network and their functions.

**Flatten Layer** - Takes the 2D image and reshapes it into a flat list of numbers.

**Dense/Hidden Layer** - This is where the actual learning happens, with neurons detecting patterns in the clothing images.

**Output Layer** - Makes the final prediction about what type of clothing item it is, choosing from 10 possible categories.

<br>

> ### <img src="https://img.shields.io/badge/Q4-4A90E2?style=flat-square" alt="4"/> What does an epoch mean in model training?

An epoch is one complete pass through the entire training dataset. So if you train for 10 epochs,
the model sees and learns from every single training image 10 times, adjusting its weights each time to get better at making predictions.

<br>

> ### <img src="https://img.shields.io/badge/Q5-4A90E2?style=flat-square" alt="5"/> Compare the predicted label and actual label for the first test image.

Both the predicted and actual labels were **9**. The model got it right! ✅ This shows the network correctly identified the first test image.

<br>

> ### <img src="https://img.shields.io/badge/Q6-4A90E2?style=flat-square" alt="6"/> What could be done to improve the model's accuracy?

To improve the model's accuracy, we could use a **CNN** instead of dense layers since CNNs are better at recognizing image patterns.
We could also add more layers or neurons, train for more epochs, use dropout to prevent overfing, or try data augmentation like rotating and flipping images.

---

<div align="center">

Made with ❤️ for Deep Learning

</div>
