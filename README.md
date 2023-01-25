## Digi-Diary
A web-based application where you can feel at home. Journal about your feelings, keep track of your mood, and relax!

## Technologies
Python, Flask, Jinja, SQL, HTML, CSS

## Requirements
Flask, Python

## Instructions
Run 'flask run' to view the website

## How to use Digi-Diary!
Users will first make an account when clicking on "Register". The username must not be already taken, and the password must be at least 6 characters long, have at least one letter, and have at least one special character from a preselected sort. Once successfully logged in, the user will have access to creating diaries and viewing old diaries.

The "Create" tab at the top will lead users to a page where they are allowed to create new diary entries. Users must input a corresponding date for the entry (which they may do so from a calendar date and time selector), a title for the entry, a description of their day, and an overall mood to describe their day. After pressing the create button, users will be redirected to the entries page, where they are able to view the entry they just submitted, and any previous entries if they exist.

The "Settings" tab leads users to a page that allows them to change their password, by clicking on a change password button which leads them to a form where they are able to enter in their old password and enter in a new password they would like to have it set to.

The logout button at the top right allows users to log out of the website securely once they are done with the diary!

## About the Files
Diary2 Details:

- In our folder static, we have our CSS file.
- In our templates folder, we have all of the html templates the website uses.
- app.py is the main file we used to write all of our Python code so that we could route commands and be able to bounce between html files.
- digidiary.db is the SQL database where our users and diary table is stored.
- helpers.py is another Python file that contains some functions that we utilized in our app.py file.
