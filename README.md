
# Brickbuster

## About
Brickbuster is a tetris-alike full stack website 
Link: [brickbuster.pythonanywhere.com](http://brickbuster.pythonanywhere.com) (**adblock recommended**)

Implemented features:
- Profile: create, edit, restore password, add pfp
- Fully debugged Tetris with a scoring system
- After the game ends, score will be automatically saved
- Leaderboard has all the records
- Every user has their own record page
- Leaderborad records will load by 10-packs as the user scrolls down the page
- Saving a post uses Rest API so that a page doesn't have to be reloaded
- All the information is stored in a SQLite database that consists of 2 tables: users, scores
- Website has an admin page accessible at /admin. Login: admin, password: admin
- Website is adapted for all kinds of screens

# Setup

The first thing to do is to clone the repository:

$ git clone [https://github.com/petosbratok/[brickbuster-full-stack](https://github.com/petosbratok/brickbuster-full-stack)]

$ cd brickbuster

Install Python and Pip.
Install the dependencies:

$ pip install -r requirements.txt

Once  `pip`  has finished downloading the dependencies:

$ cd project
$ python manage.py runserver

# Main links 
Home page:  `http://127.0.0.1:8000/`<br>
Profile: `http://127.0.0.1:8000/profile`<br>
Records of a certain user: `http://127.0.0.1:8000/user/<user_id>`<br>
Leaderboard: `http://127.0.0.1:8000/scoreboard/`

