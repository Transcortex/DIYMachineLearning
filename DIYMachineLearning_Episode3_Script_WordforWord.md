
# DIYMachineLearning YouTube Series - Episode 3 Script (Word-for-Word)

## Episode 3: Installing TensorFlow in WSL

---

### 00:00 - 00:30 | Introduction
- **Script:** "Welcome back to DIYMachineLearning! Today, we’ll install TensorFlow, a popular tool for building machine learning models. TensorFlow is a core library that makes it easy to start creating models, and we’ll set it up in our WSL environment."

---

### 00:30 - 02:00 | Setting Up a Python Virtual Environment
- **Script:** "We’ll use a virtual environment to keep everything organized. Type `sudo apt install python3-venv` to install the venv tool if it’s not already installed. Now, create the virtual environment by typing `python3 -m venv tf_env`. Then, activate it with `source tf_env/bin/activate`. This keeps packages isolated for each project."

---

### 02:00 - 05:00 | Installing TensorFlow (Pinned Version)
- **Script:** "With our virtual environment active, let’s install TensorFlow. Type `pip install tensorflow==2.11.0` to install version 2.11.0. Using a pinned version ensures compatibility across our tutorials and avoids future changes that might affect our code."

---

### 05:00 - 07:00 | Verifying the Installation
- **Script:** "Let’s check if TensorFlow installed correctly. Type `python` to open Python, then enter `import tensorflow as tf` and `print(tf.__version__)`. You should see version 2.11.0 displayed, confirming it’s ready to use."

---

### Closing
- **Script:** "Great! We’ve successfully installed TensorFlow. In the next episode, we’ll start working with data preparation and learn about ETL—Extract, Transform, Load. Don’t forget to like, subscribe, and hit the bell to follow along with DIYMachineLearning!"

---
