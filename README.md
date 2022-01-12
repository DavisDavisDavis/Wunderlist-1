<img src="https://media0.giphy.com/media/2rKDe8JpAEatWVamEe/giphy.gif">

# Wunderlist

This is the final project of 2021 in the web development course at Yrgo (WU21). The aim is to create a website where a user can sign up, log in and create lists and tasks. The website is built using php, javascript and css.

# Installation

Either visit the demo here: https://deliciaes.com

Or download this repository and launch a localhost to run it locally on your machine.

# Code Review

Code review written by [Amanda Hultén](https://github.com/amandahulten).

1. `store.php` - Instead of having the queries for tasks and lists in the same file, you could divide them into seperate files under seperate folders for a better structure. 
2. `wunderlist.js` - Your JS file is full of information and comments, I would recommend to divide the code into different files for better readability. 
3. `uploads` - You can move your uploads file to .gitignore since you only have it to store information. 
4. `users- all files` - You don't need to write "else" in your if statements. Your redirect will end the statement if fulfilled and otherwise jump to the next line of code.
5. `wunderlist.php` - You could set a maxlength on your task-inputs to prevent the user from writing long titles or descriptions that would affect your styling.
6. `wunderlist.php` - Your class-names are a bit general in parts of your code, for example container and row. I would recommend to name them more specificly even if they have the same styling, to get a better understanding of your css-file. 
7. `store.php` - As a user I would prefer to choose whether I want a descriptions on my tasks or not.
8. `app/` - You don't need to write FILTER_SANITIZE_STRING on your php variables since you use htmlspecialchars.
9. `wunderlist.js` - Commented code is to prefer, but all the comments when getting elements seems a bit unnecessary. Good variable-names is enough (which you have).
10. `overall` - Really good job with your error and success-messages, you keep the user updated at all times! Overall a really good site!

# Testers

Tested by the following people:

1. Agnes Skönvall
2. Sofia Dersén
