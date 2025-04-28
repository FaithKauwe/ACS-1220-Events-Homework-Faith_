# Events App

To run this code, start by cloning this repository to your computer. Then in a terminal, navigate to the project folder.
**To run the code**, navigate to the project folder and run the following to create a virtual environment and install the required packages:

```
python3 -m venv venv
source venv/bin/activate


To install dependencies, run:

```
pip3 install -r requirements.txt
```

Then rename the `.env.example` file as `.env`:

```
cp .env.example .env
```

Then you can run the server:

```
python3 app.py
```

yellow squiggles under sqlAlchemy, tried to install with pip install sqlalchemy, but it was already installed 
I'm in VS Code and in the terminal, I ran which python and got 
/Users/faithkauwe/Documents/Projects/ACS1220Auth/ACS-1220-Events-Homework/venv/bin/python

then I did command_shift-p to bring up my command palette, selected Select interpreter and got a dropdown menu 

I selected the one ending in /venv/bin/python and that seemed to correct the import errors!