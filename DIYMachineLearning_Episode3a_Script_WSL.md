
# DIYMachineLearning YouTube Series - Episode 3a Script

## Episode 3a: Installing Jupyter Notebook Locally in WSL with a Virtual Environment

---

### 00:00 - 00:30 | Introduction
- **Script:** "Welcome back to DIYMachineLearning! Today, we’re setting up Jupyter Notebook, an interactive tool that’s perfect for machine learning. Jupyter lets you write and run code in chunks, add explanations, and visualize data—all in one place. We’ll install Jupyter Notebook within our WSL environment, and use a virtual environment to keep everything organized."
- **Screen Capture:** Show a Jupyter Notebook interface with labeled sections, such as ‘Code Cell’, ‘Markdown’, and ‘Output’.
- **Effort:** Explain why Jupyter is popular among data scientists, emphasizing its interactive nature and versatility for both coding and documenting.

---

### 00:30 - 02:30 | Activating the Virtual Environment in WSL
- **Script:** "To start, let’s activate our virtual environment created in WSL during Episode 3. Using virtual environments helps us keep project dependencies separate. If you don’t have a virtual environment yet, check Episode 3 for setup instructions."
- **Code:**
  ```bash
  source tf_env/bin/activate  # or .\tf_env\Scripts\activate on Windows
  ```
- **Screen Capture:** Show the command in the WSL terminal and confirm activation with the environment name appearing in the prompt.
- **Effort:** Reinforce why using virtual environments in WSL keeps the development environment contained and organized.

---

### 02:30 - 04:00 | Installing Jupyter Notebook in WSL
- **Script:** "With our virtual environment active in WSL, we’re ready to install Jupyter Notebook. Installing Jupyter within this environment ensures that it will only be available when our environment is active, keeping your overall system clean."
- **Code:**
  ```bash
  pip install jupyter
  ```
- **Screen Capture:** Show the installation process in the WSL terminal, confirming Jupyter is installed without issues.
- **Effort:** Explain that this setup keeps Jupyter and its dependencies isolated within the WSL environment.

---

### 04:00 - 06:30 | Launching Jupyter Notebook in WSL and Accessing it in the Browser
- **Script:** "Now that Jupyter is installed, let’s launch it! In the WSL terminal, type `jupyter notebook`. Jupyter will start a server and provide a local link. Open this link in your browser to access the Jupyter Notebook interface."
- **Code:**
  ```bash
  jupyter notebook
  ```
- **Screen Capture:** Show starting Jupyter in WSL and navigating to the browser to open the notebook interface.
- **Effort:** Explain that the server runs within WSL, and the browser allows easy access to work on notebooks.

---

### 06:30 - 08:00 | Exploring the Jupyter Notebook Interface and Key Concepts
- **Script:** "Let’s get familiar with the Jupyter Notebook interface. Each notebook is composed of cells, which can hold code, markdown for explanations, or display outputs. Code cells allow you to write and run Python code, and Markdown cells let you add descriptions, making it easy to document your work. Let’s try creating a code cell and typing a simple command."
- **Code:**
  ```python
  print("Hello, Jupyter!")
  ```
- **Screen Capture:** Demonstrate creating a code cell, running the command, and explaining each cell type.
- **Effort:** Highlight the interactive nature of Jupyter, allowing users to combine code with explanations and results in one document.

---

### 08:00 - 09:30 | Saving and Closing a Notebook
- **Script:** "To save your notebook, go to ‘File’ > ‘Save and Checkpoint’. This saves your progress. To close the notebook, press `Ctrl + C` in the WSL terminal to stop the Jupyter server. If you need to open it again, simply activate your virtual environment in WSL and type `jupyter notebook`."
- **Screen Capture:** Show saving the notebook, closing the server in the terminal, and restarting it as needed.
- **Effort:** Provide clear instructions for saving and closing Jupyter, emphasizing the workflow within WSL.

---

### Closing
- **Script:** "That’s it for installing and running Jupyter Notebook in WSL! You now have a powerful tool for experimenting with code, documenting your process, and visualizing results, all within a well-organized virtual environment. In the next episode, we’ll dive back into our ML journey by setting up TensorFlow. Don’t forget to like, subscribe, and hit the bell to stay tuned!"
- **Screen Capture:** Outro screen with the series name, episode number, and a teaser for Episode 4 on continuing the ML setup.
- **Effort:** Encourage viewers to experiment with Jupyter for their ML projects, reinforcing its value for interactive learning.

---
