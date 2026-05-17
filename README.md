# INST447-Final-Project
---

## User guide to running the code

1. Download the installer for Positron from this [link](https://positron.posit.co/download.html). Make sure to accept the license agreement by checking the box. Choose the file that matches your platform. The platform information is available if you visit System Information for Windows or About This Mac for MacOS.

2. Clone the repository from this [link](https://github.com/lejio/INST447-Final-Project/tree/main) using `git clone git@github.com:lejio/INST447-Final-Project.git` for SSH.

3. Open the “INST447-Final-Project” folder in Positron by clicking on the Open button with the file icon at the top left of the application.

4. Go to the terminal at the bottom half of the interface. Make sure that you are in the correct folder. Your path should have “INST477-Final-Project.” If not, use the cd command to get there. Here is a [tutorial](https://tutorials.codebar.io/command-line/introduction/tutorial.html) on using the command line.

5. Make a virtual environment by running `python3 -m venv .venv`.

6. Activate the environment using `source .venv/bin/activate` for MacOS/Linux. For Windows Powershell, use `.\venv\Scripts\Activate.ps1`.

7. Install the dependencies from the requirements.txt file using `pip install -r requirements.txt`.

7.5. Check that quarto is installed in the environment using `quarto -v` in the terminal. If it isn’t installed, install it using `brew install --cask quarto` for MacOS if you have Homebrew. Otherwise, you can install it from this [website](https://quarto.org/docs/get-started). You may have to restart Positron and your terminal.

8. Open the .qmd file by clicking on it from the file explorer and render it by clicking the “Preview” button close to the top of the opened file. A side bar on the right should open, and there should be a square with an arrow icon. Clicking the icon will open a new browser window, which will give you access to the notebook code and output running on localhost. Use CTRL + C to quit.
