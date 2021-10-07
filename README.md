# Team Profile Generator

![badge](https://img.shields.io/badge/license-MIT-brightgreen)

## Descripion

A webpage that displays my team's basic info.

Acceptance Critera:

GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team rost
er based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the ema
il with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email a
ddress, and office number
WHEN I enter the team manager’s name, employee ID, email address, and off
ice number
THEN I am presented with a menu with the option to add an engineer or an
intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub us
ername, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and
I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
The following image shows the generated HTML’s appearance and functionality. The styling in
the image is just an example, so feel free to add your own styles:

## Installation

- npm init
- npm i inquirer
- npm i jest

## Usage

npm test at root of the file to test app
node index.js
