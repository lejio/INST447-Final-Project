# INST447-Final-Project
---

To run locally follow these instructions:

This assumes you have Python and Git installed on your computer.

The following instructions is for **MacOS** and **Unix** environments only. 

First clone the repository:

Clone the repository
```sh
git clone git@github.com:lejio/INST447-Final-Project.git
```

```
cd ./INST447-Final-Project
```

Make an environment
```sh
python3 -m venv .venv
```

Activate said environment
```sh
source .venv/bin/activate
```

Install required packages in requirements.txt
```sh
pip install -r requirements.txt
```

Create a ```.env``` file and paste the secrets in there.

Finally, run main.py
```sh
python main.py
```

Quarto install instructions:

Copy and paste this in the command line if you are on linux to install quarto
```
# Get the latest .deb
wget https://quarto.org/download/latest/quarto-linux-amd64.deb

# Install it
sudo dpkg -i quarto-linux-amd64.deb

# Fix any missing deps if needed
sudo apt-get install -f

# Verify
quarto --version
```

Then you can run these commands:

```
quarto preview inst447-group10-final-submission.qmd
```

or:

```
quarto render inst447-group10-final-submission.qmd
```