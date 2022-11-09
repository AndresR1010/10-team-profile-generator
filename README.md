# 10-team-profile-generator

# Description

This project is created to run from the command line in order to create a profile of their team members with their name, id, email and including their role. Along with their role, the user will be asked a specific question that correlates to that position within the team. Then it will take the users input to generate a HTML file using the team information.

# Installation

You will first need to install node.js to operate this project. To do so, first go to the Node.js website and follow the instructions to install Node.js. Once you have Node.js installed, use git to clone the project repository from GitHub. After cloning, run 'npm i' or 'npm install' from the command line in the directory of the project to install all neccessary dependencies for this project. then you will be able to use the application.

# Usage

Using the command line from the main directory of the project repository,run 'npm start' in order to initialize the app.
You will be given a welcome message and asked to confirm if you want to continue with the app, input 'y' to continue, or input 'n' to close app.
If you chose to continue you will be prompted to input the employee's name, then id, and then their email.
Then you will be asked what the role the employee works as. Select their role using the arrow keys and press the 'enter' key on your keyboard.
Depending on the role you chose you will be asked to input either their office number, GitHub username, or the name of their school.
Now that you have inputted all the required employee information, confirm whether you want to add an additional employee with 'y' or generate the HTML file with 'n'.

# Demo

[Walkthrough Demo](https://drive.google.com/file/d/1O_t6Eux3919BQqkJTxyhV1oJ49uN35dC/view?usp=sharing)

# Technology/Libraries

Node.js
Inquirer
Jest
Bootstrap
Font Awesome

Tests
Run 'npm test' from the command line while located in the directory of the project repository to run jest.
