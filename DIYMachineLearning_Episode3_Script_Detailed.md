
# DIYMachineLearning YouTube Series - Episode 3 Script

## Episode 3: Installing TensorFlow in WSL

---

### 00:00 - 00:30 | Introduction
- **Script:** "Welcome back to DIYMachineLearning! Today, we’ll be installing TensorFlow in our WSL environment. TensorFlow is a core library for building machine learning models, and we’ll be using it in future episodes to create and train models."
- **Screen Capture:** Friendly intro screen with episode title and a visual of the TensorFlow logo to introduce the library.
- **Effort:** Provide a brief explanation of TensorFlow’s importance in ML, ensuring beginners understand its role in upcoming projects.

---

### 00:30 - 02:00 | Setting Up a Python Virtual Environment
- **Script:** "To keep our projects organized and prevent package conflicts, let’s set up a Python virtual environment. Virtual environments allow us to install libraries in a separate space for each project. To start, install the Python virtual environment package by typing `sudo apt install python3-venv`. Then, create a virtual environment by typing `python3 -m venv tf_env`, where `tf_env` is the name of our environment. Finally, activate it by typing `source tf_env/bin/activate`."
- **Code:**
  ```bash
  sudo apt install python3-venv
  python3 -m venv tf_env
  source tf_env/bin/activate
  ```
- **Screen Capture:** Show each command in the terminal, highlighting the activation of the virtual environment.
- **Effort:** Emphasize the benefits of virtual environments for managing dependencies, especially as we begin to work with different ML libraries.

---

### 02:00 - 05:00 | Installing TensorFlow (Pinned Version)
- **Script:** "With our virtual environment activated, we’re ready to install TensorFlow. It’s good practice to install a pinned version of TensorFlow to avoid compatibility issues. Type `pip install tensorflow==2.11.0` to install TensorFlow version 2.11.0. This ensures that all our code works as expected, as newer versions sometimes introduce changes that can break older code."
- **Code:**
  ```bash
  pip install tensorflow==2.11.0
  ```
- **Screen Capture:** Show the installation process in the terminal and explain what is happening during installation.
- **Effort:** Explain the concept of pinned versions and reassure beginners that using a specific version will make future tutorials smoother.

---

### 05:00 - 07:00 | Verifying the Installation
- **Script:** "To confirm TensorFlow is installed correctly, open Python by typing `python`, then type `import tensorflow as tf` and `print(tf.__version__)`. You should see the version number 2.11.0 displayed, which tells us TensorFlow is successfully installed and ready to use."
- **Code:**
  ```python
  python
  import tensorflow as tf
  print(tf.__version__)
  ```
- **Screen Capture:** Show each command in the Python interpreter, highlighting the output showing the TensorFlow version.
- **Effort:** Emphasize the importance of verifying installations to avoid issues later on, and reinforce the idea that seeing the correct version confirms successful setup.

---

### Closing
- **Script:** "Great work! We now have TensorFlow installed and ready to go in our WSL environment. In the next episode, we’ll start exploring data preparation for machine learning, covering the basics of ETL—Extract, Transform, Load. Don’t forget to like, subscribe, and hit the bell icon to keep up with DIYMachineLearning!"
- **Screen Capture:** Outro screen with the series name, episode number, and a teaser for the next episode on ETL basics.
- **Effort:** Keep a motivational tone, encouraging viewers to stay engaged with the series as we move closer to building actual ML models.

---
