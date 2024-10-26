
# DIYMachineLearning YouTube Series - Episode 3 Script

## Episode 3: Installing TensorFlow in WSL

---

### 00:00 - 00:30 | Introduction
- **Script:** "Welcome back to DIYMachineLearning! Today, we’ll be installing TensorFlow in our WSL environment. TensorFlow is a core library for building machine learning models, and we’ll be using it in future episodes to create and train models."
- **Screen Capture:** Friendly intro screen with episode title and a visual of the TensorFlow logo to introduce the library.
- **Effort:** Provide a brief explanation of TensorFlow’s importance in ML, ensuring beginners understand its role in upcoming projects.

---

### 00:30 - 02:30 | Setting Up a Conda Environment and Explaining Virtual Environments
- **Script:** "To keep our projects organized and prevent package conflicts, let’s set up a virtual environment using Conda. Virtual environments create an isolated space for each project, so if you install specific packages here, they won’t interfere with packages in other environments. Conda is a popular package manager that makes creating environments simple and helps manage dependencies effectively."
  - "To start, make sure Conda is installed. If you haven’t installed Conda, you can download Anaconda from the official website. Once installed, create a new environment for TensorFlow by typing `conda create -n tf_env python=3.8`."
  - "The `-n tf_env` part names the environment ‘tf_env’, and specifying `python=3.8` ensures that this environment uses Python 3.8."
- **Code:**
  ```bash
  conda create -n tf_env python=3.8
  conda activate tf_env
  ```
- **Screen Capture:** Show each command in the terminal, highlighting the creation and activation of the Conda environment.
- **Effort:** Emphasize why isolated environments are beneficial, particularly as beginners start to explore and experiment with different libraries.

---

### 02:30 - 05:00 | Installing TensorFlow in the Conda Environment (Latest Version)
- **Script:** "With our Conda environment `tf_env` activated, let’s install TensorFlow. Using Conda to install packages ensures compatibility between libraries and dependencies. Type `conda install tensorflow` to install the latest version of TensorFlow in this environment."
- **Code:**
  ```bash
  conda install tensorflow
  ```
- **Screen Capture:** Show the installation process in the terminal and explain what is happening during installation.
- **Effort:** Explain how Conda automatically handles dependencies and why it’s helpful to use Conda for managing complex libraries like TensorFlow.

---

### 05:00 - 07:00 | Verifying the Installation
- **Script:** "To confirm TensorFlow is installed correctly, enter Python by typing `python`. Then, type `import tensorflow as tf` and `print(tf.__version__)`. This command should display the TensorFlow version number, confirming that our installation is successful and ready to use."
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
- **Script:** "Great work! We now have TensorFlow installed and ready to go in our Conda environment. In the next episode, we’ll start exploring data preparation for machine learning, covering the basics of ETL—Extract, Transform, Load. Don’t forget to like, subscribe, and hit the bell icon to keep up with DIYMachineLearning!"
- **Screen Capture:** Outro screen with the series name, episode number, and a teaser for the next episode on ETL basics.
- **Effort:** Keep a motivational tone, encouraging viewers to stay engaged with the series as we move closer to building actual ML models.

---
