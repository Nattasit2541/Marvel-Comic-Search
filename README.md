# Marvel-Comic-Search
SI 507 Final Project

This project is aiming to build an interactive application to give users recommendation based on their Marvel comic preferences. I use comic data base from Marvel API (https://developer.marvel.com/).

To use the program, you can just run the file named "app.py" then use the Flask link to access the comic recommendation website.

PACKAGE REQUIREMENT
- requests
- json
- os
- hashlib
- time

Data Structure
I put my comic data (JSON) into Class of Comic. Then, I use filter question and questions in a tree structure to find the corresponding comic preference.
