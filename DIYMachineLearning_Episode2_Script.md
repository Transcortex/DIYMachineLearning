
# DIYMachineLearning YouTube Series - Episode 2 Script

## Episode 2: Creating Your Developer Environment in WSL

---

### 00:00 - 00:30 | Introduction
- **Script:** "Welcome back to DIYMachineLearning! Today, we’re setting up a developer environment in WSL to keep everything organized and ready for machine learning projects."
- **Screen Capture:** Friendly intro screen with episode title and a brief visual overview of the environment setup process.
- **Effort:** Use a welcoming tone, reminding viewers that an organized environment is key for effective project work.

---

### 00:30 - 02:30 | Creating Folders for Development
- **Script:** "To keep our work organized, let’s create folders for our projects. Open Ubuntu and type `mkdir Projects` to create a Projects folder. Inside this folder, we can create subfolders for each project we work on."
- **Code:**
  ```bash
  mkdir Projects
  cd Projects
  ```
- **Screen Capture:** Show the Ubuntu terminal where you type the commands, highlighting each command as it is typed and the folder structure being created.
- **Effort:** Emphasize why keeping files organized is essential for managing multiple ML projects and datasets.

---

### 02:30 - 04:30 | Installing Git
- **Script:** "Now that we have a Projects folder, let’s install Git. Git is a tool that helps us manage and track changes in our code. To install Git, type `sudo apt install git`. Once installed, type `git --version` to check if it’s correctly installed."
- **Code:**
  ```bash
  sudo apt install git
  git --version
  ```
- **Screen Capture:** Show the terminal as you install Git, then display the command to verify the installation.
- **Effort:** Explain the importance of version control in programming, even for beginners, and reassure viewers that Git will help them keep track of their work.

---

### 04:30 - 08:00 | Basic Command Line Navigation
- **Script:** "Now that we’ve created folders and installed Git, let’s go over some basic navigation commands in the command line. `ls` lists files and folders in the current directory, and `cd` changes directories. For example, `cd Projects` takes us into our Projects folder. If you want to go back up a level, type `cd ..`."
- **Code:**
  ```bash
  ls
  cd Projects
  cd ..
  ```
- **Screen Capture:** Show the commands being used in the terminal, including navigating into and out of folders.
- **Effort:** Walk through each command slowly, explaining each function, to ensure beginners feel comfortable moving around their directory structure.

---

### 08:00 - 10:00 | Overview of Text Editors (Nano and Vim)
- **Script:** "Lastly, let’s look at basic text editors available in Linux. First, try opening Nano, which is a beginner-friendly editor, by typing `nano test.txt`. This command opens a new text file. Type some text, then press `Ctrl + X` to exit, `Y` to save changes, and Enter to confirm. Another popular editor is Vim, but it has a steeper learning curve. For simplicity, let’s stick with Nano for now."
- **Screen Capture:** Show opening, typing in, and saving a file in Nano to demonstrate its ease of use.
- **Effort:** Recommend Nano for beginners as it’s simpler than Vim, and clearly explain the steps for saving and exiting the editor.

---

### Closing
- **Script:** "That’s it for Episode 2! You now have a workspace set up in WSL and are ready to start working on machine learning projects. In the next episode, we’ll install TensorFlow, one of the essential libraries for machine learning in Python. Make sure to like, subscribe, and follow along with DIYMachineLearning for more episodes!"
- **Screen Capture:** Outro screen with the series name, episode number, and a teaser for the next episode.
- **Effort:** Keep a motivating tone, and emphasize the importance of having a structured setup as we move into ML tools in future episodes.

---
