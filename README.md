# Team Generator

## Repository & Video Walkthrough

Video Walkthrough Command Line: https://vimeo.com/639857399/3f490f714f

Video Walkthrough of HTML Output: https://vimeo.com/640100322/91f12b119f

[Repository](https://github.com/eduardvoicu/team-generator)

## Directory

1. [User Story](#user-story)
2. [Installation](#installation)
3. [Application Preview](#application_preview)
4. [Technology](#technology)
5. [License](#license)
6. [About](#about)

## User Story
```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```
```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted 
team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of 
the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, 
and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or 
to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and 
GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and 
I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```
## Installation

Copy and run the code below to get started with orignal package and get all dependencies:
```
git clone git@github.com:eduardvoicu/team-generator.git
cd team-generator
```
Start application by running this command:
```
node app.js
```
Answer the prompts in the command line.

Upon completion, you can view the html rendered output in the output `team.html`

## Application Preview
Full Preview
![Preview GIF](images/tty.gif)

Tests Preview
![Preview Test](images/test.gif)

![Team Profile](images/teamprofile.png)

## Technology

Prerequsites:
- [Node.js](https://nodejs.org/en/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Additional Packages unique to this application:
- [Inquirer](https://www.npmjs.com/package/inquirer)

## License

MIT License

Copyright (c) 2021

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## About
Eduard Voicu
- [GitHub](https://github.com/eduardvoicu)
- [LinkedIn](https://www.linkedin.com/in/eduardvoicu/)