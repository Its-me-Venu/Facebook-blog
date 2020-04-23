# Facebook-blog

It is a Flask social blogging application web application in which authenticated users can follow\unfollow each other, as well as creating and editing their own blog posts and comments.

Prerequisites:

The application was built using Python, so you should ensure you have it installed on your machine.

You can find the application requirements in the requirements folder.

Usage:

Clone this repository and go to the directory and create a new virtual environment to create isolated Python environment. Note: I highly recommend using Virtualenv.

Install the application requirements:

pip install -r requirements\dev.txt

set FLASK_APP=run.py

Run the CLI deploycommand to create the database:
flask deploy

Run the application and go to localhost:5000 to see the application running:

flask run

