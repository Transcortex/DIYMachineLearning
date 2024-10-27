
# DIYMachineLearning YouTube Series - Episode 3a Script

## Episode 3a: Installing Jupyter Notebook Locally with a Virtual Environment

---

### 00:00 - 00:30 | Introduction
- **Script:** "Welcome back to DIYMachineLearning! Today, we’re taking a quick detour to set up Jupyter Notebook, an interactive environment that’s popular for data science and machine learning. Jupyter Notebooks are great for experimenting, writing code, and documenting your process all in one place. We’ll install Jupyter locally within our Python virtual environment to keep everything organized and streamlined."
- **Screen Capture:** Intro screen with episode title and an example of a Jupyter Notebook interface.
- **Effort:** Highlight the benefits of Jupyter for ML projects and explain that it’s widely used by data scientists and developers alike.

---

### 00:30 - 02:30 | Activating the Virtual Environment
- **Script:** "To start, let’s activate the Python virtual environment we created earlier in Episode 3. Virtual environments help us manage dependencies without affecting other projects, so installing Jupyter within this environment keeps everything contained. If you don’t have a virtual environment yet, check out Episode 3 for setup instructions."
- **Code:**
  ```bash
  source tf_env/bin/activate  # or .\tf_env\Scripts\activate on Windows
  ```
- **Screen Capture:** Show the command in the terminal and confirm activation of the virtual environment.
- **Effort:** Remind viewers why using virtual environments keeps their ML setup clean and organized.

---

### 02:30 - 04:00 | Installing Jupyter Notebook
- **Script:** "Now that our virtual environment is active, let’s install Jupyter Notebook. Type the following command to install Jupyter within the current environment."
- **Code:**
  ```bash
  pip install jupyter
  ```
- **Screen Capture:** Show the installation process in the terminal, ensuring the Jupyter package installs correctly.
- **Effort:** Explain that installing within the virtual environment makes Jupyter accessible only within this project, keeping the system uncluttered.

---

### 04:00 - 06:30 | Starting Jupyter Notebook
- **Script:** "With Jupyter installed, let’s launch it! Simply type `jupyter notebook` to start the Jupyter server. This will open a new tab in your browser, where you can create and edit notebooks directly."
- **Code:**
  ```bash
  jupyter notebook
  ```
- **Screen Capture:** Show the terminal command to start Jupyter and navigate to the browser where the Jupyter interface opens.
- **Effort:** Walk through the steps clearly so beginners understand how to open and access the Jupyter interface.

---

### 06:30 - 08:00 | Creating and Saving a Test Notebook
- **Script:** "Now that Jupyter is running, let’s create a simple notebook to test everything. Click on ‘New’ > ‘Python 3’ to open a new notebook. Try typing a simple Python command, like `print('Hello, Jupyter!')`, and run it by pressing Shift + Enter. Once you’re done, save the notebook by clicking on ‘File’ > ‘Save and Checkpoint’."
- **Screen Capture:** Demonstrate creating a new notebook, entering a command, and saving the notebook.
- **Effort:** Reinforce the value of Jupyter for testing code snippets and keeping work organized within the notebook format.

---

### 08:00 - 09:30 | Closing the Jupyter Notebook Server
- **Script:** "To stop the Jupyter server, simply go back to the terminal where you launched it, and press `Ctrl + C`. Jupyter will prompt you to confirm shutdown. This stops the server, and you can reactivate it anytime by re-running `jupyter notebook` within the virtual environment."
- **Screen Capture:** Show the shutdown command and explain the process of stopping and restarting the Jupyter server.
- **Effort:** Provide clear instructions to prevent confusion, especially for beginners unfamiliar with stopping background processes.

---

### Closing
- **Script:** "And there you have it—Jupyter Notebook is now set up locally within our virtual environment! Jupyter is a fantastic tool for experimenting and documenting your machine learning journey. In the next episode, we’ll continue with our ML setup by installing TensorFlow and building our first model. Don’t forget to like, subscribe, and hit the bell to keep learning with DIYMachineLearning!"
- **Screen Capture:** Outro screen with the series name, episode number, and a teaser for Episode 4 on model setup.
- **Effort:** Encourage viewers to explore Jupyter by creating their own test notebooks, reinforcing the tool’s usefulness in their learning journey.

---
