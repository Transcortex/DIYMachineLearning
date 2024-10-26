
# DIYMachineLearning YouTube Series - Episode 1 Script

## Episode 1: Setting Up Windows 11 with WSL for Machine Learning

---

### 00:00 - 00:30 | Introduction
- **Script:** "Welcome to DIYMachineLearning! I’m excited to take you from setting up your machine to building machine learning models. Today, we’ll set up a development environment on Windows 11 using WSL, which stands for Windows Subsystem for Linux. This setup allows us to run Linux directly on Windows without needing another machine."
- **Screen Capture:** Friendly, welcoming intro screen with episode title.
- **Effort:** Friendly and approachable, explaining how this setup benefits ML beginners on Windows.

---

### 00:30 - 01:30 | Why WSL?
- **Script:** "Why use WSL? If you’re on Windows, WSL gives you access to Linux tools and frameworks, essential for machine learning. Linux is the go-to system for developers due to its flexibility and availability of open-source tools. By using WSL, we get these benefits without needing a separate Linux computer."
- **Screen Capture:** Simple graphic or text overlay with WSL benefits.
- **Effort:** Emphasize why WSL helps avoid additional setup, making it beginner-friendly.

---

### 01:30 - 03:30 | Enabling WSL
- **Script:** "To get started, open your Start Menu, type ‘Turn Windows features on or off,’ and click it. Here, scroll down and check the box for **Windows Subsystem for Linux**. Then, click **OK** and restart your computer when prompted."
- **Screen Capture:** Show each step in the Windows menu, highlighting the WSL checkbox.
- **Effort:** Go slowly here, as this is the first technical step for beginners.

---

### 03:30 - 05:30 | Installing Ubuntu
- **Script:** "Once we’ve restarted, go to the Microsoft Store, search for ‘Ubuntu,’ and select **Get** to download and install it. After installation, open Ubuntu. It’ll ask you to set a username and password for Linux. Make sure to remember these, as we’ll use them often."
- **Screen Capture:** Show each step in the Microsoft Store and installation, highlighting key points like setting a password.
- **Effort:** Make the steps clear, as some beginners may not be familiar with the Microsoft Store or Linux username setup.

---

### 05:30 - 07:30 | Updating and Upgrading Linux
- **Script:** "Now we’re in Ubuntu, we need to update it to make sure we’re using the latest versions of all tools. Type `sudo apt update` and press Enter. This command checks for updates. Then type `sudo apt upgrade` to install the updates. You might have to type ‘Y’ to confirm."
- **Code:**
  ```bash
  sudo apt update
  sudo apt upgrade
  ```
- **Screen Capture:** Show these commands being typed, with close-ups on confirmations.
- **Effort:** Explain the purpose of `sudo` as “superuser do,” making beginners comfortable with admin commands.

---

### 07:30 - 09:30 | Installing Essential Developer Tools
- **Script:** "Let’s install essential developer tools. These will help us run machine learning code. Type `sudo apt install build-essential` to install compilers, then type `sudo apt install python3-pip` to install pip, which we’ll use to install Python packages."
- **Code:**
  ```bash
  sudo apt install build-essential
  sudo apt install python3-pip
  ```
- **Screen Capture:** Show each command, explaining each tool’s role.
- **Effort:** Reinforce the importance of each tool, noting that `build-essential` helps install necessary compilers.

---

### 09:30 - 10:00 | Testing the Setup
- **Script:** "Finally, let’s check if everything is installed correctly. Type `python3 --version` to see if Python is installed, and `pip3 --version` to check pip. If you see version numbers, you’re good to go!"
- **Code:**
  ```bash
  python3 --version
  pip3 --version
  ```
- **Screen Capture:** Show typing and outputs to confirm installation.
- **Effort:** Emphasize that seeing the version numbers means everything is set up correctly.

---

### Closing
- **Script:** "That’s it for Episode 1! We now have a Linux environment in Windows 11. In the next episode, we’ll install TensorFlow to start building ML models. Don’t forget to like, subscribe, and hit the bell to follow along with DIYMachineLearning!"
- **Screen Capture:** Friendly outro screen with series name, episode number, and next episode teaser.
- **Effort:** Reassure beginners and encourage them to follow along in future episodes.

---
