# PhotoStore
A **buggy** web application to store and share your photos

## Before you start
This project is divided into two branches
- `cybersec` - Cyber Security
  - finding bugs
  - patching them

- `main` - Web Development
  - improvements or additions in frontend and/or backend

### For Cyber Security
Please refer to [`cybersec`](https://github.com/opencodeiiita/PhotoStore/tree/cybersec) branch

### For Web Development
Other than the issues provided in [Issues](https://github.com/opencodeiiita/PhotoStore/issues)<br>
You are **not restricted** from adding your own features<br>
However, it is upto the organizers and/or mentors whether to reward points for it or not<br>

For any new feature that you come up with<br>
please attach screenshots with _proper details_ in your Pull request

It will make it easier for the mentors to get to know about feature

## Requirements
- Basic understanding of backend and frontend
- Python3 (3.9.9 or newer is expected)
- `pip` (package installer for Python)
- `virtualenv`

Read more about `virtualenv` [here](https://docs.python.org/3/tutorial/venv.html)

## Setup
Assuming you have **cloned** this repository, following instructions will get your server running

```bash
# Create a virtual environment
virtualenv venv

# Activate it
# for Linux
source venv/bin/activate

# for Windows
.\venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

# Run the server
python server.py

# For debugging, to see server requests
python app.py

# Server will run on `localhost:8080`
# you can modify this in `app.py` and/or `server.py`

# To clean the database, reset the web application
# remove `photostore.db` and clear the `uploads` directory

# for Linux
rm photostore.db uploads/*

# for Windows
del photostore.db uploads/*
```

## Previews
### Register an account
![sign-up](./preview/sign-up.png)

### View the gallery
![gallery](./preview/gallery.png)

## Issues
Go through the code, visit the web application<br>
See [Issues](https://github.com/opencodeiiita/PhotoStore/issues) to know more

## Queries
For any queries related to this project, please keep them to Discord only

<b>Have fun :smile:</b>
