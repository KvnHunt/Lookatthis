# Lookatthis
SVG
SVG-Logo-Maker
Week-10 Challenge



Table of Contents
Description

Live-Screen-Recording-of-Application-Functionality

Screenshots

Technologies-Used

Installation

Credits

Features

Usage-Information

Contribution-Guidelines

Test-Instructions

License

Questions

 ## Description
This application was built as a way to allow freelance web developers to create simple logos for their clients and projects so that they can forego paying a graphic designer. It utilizes inquirer to prompt the user within the command line for how they would like their logo to look (ie. what text they would like their logo to display (up to 3 characters in length), the color of that text, the shape of their logo (triangle, square, or circle) and the color of that shape.) Once the user answers all prompts, then an SVG file is written using their selections to generate a logo. This application also is my first implementation of unit testing within my applications. It utilizes one test suite, with three tests, all which are simply testing that the code base is delivering back correct shapes and colors. Building this application served as yet another look at what back-end developers can do without the use of a UI (user interface). I learned the value of unit testing and how this simple example used within my application can be expanded upon for much larger code bases and it's necessity when many developers are all contributing to the same project. Lastly, I have noticed myself starting to think more and more like a developer, adding some minor error handling with the first user prompt: not allowing for a logo to be generated when more than three characters are entered by the user. Future development on this application could start with adding on more error handling (SVG colors).

Live Screen Recording of Application Functionality


## Screenshots
Logo Generation
![Screenshots](./Screenshots/Capture.PNG) 
![Screenshots](./Screenshots/Capture2.PNG)
![Screenshots](./Screenshots/Capture3Circle.PNG)


## Examples of Generated Logos
![RenderImages](./Screenshots/RenderImages/Circle.PNG)
![RenderImages](./Screenshots/RenderImages/Square.PNG)
![RenderImages](./Screenshots/RenderImages/Triangle.PNG)

## Technologies Used
This project is powered by Node.js v16, utilizes inquirer v8.2.4 (node package manager), and file system module (node package manager). It also employs jest v29.5.0 (node package manager) for the unit testing conducted in this application.

## Installation
Clone the repo: git clone https://github.com/KvnHunt/Lookatthis.git

Open in VS Code. If you do not have VS code you must install it.

Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install inquirer and jest directly from the command line, to do so the command for inquirer will be npm i inquirer@8.2.4 to install v8.2.4 of the inquirer, and npm i jest to install the latest version of jest).

To run the application, within the terminal, type the command node index.js.

## Credits


## Features
Features of this application include the users ability to generate logos quickly and easily through the use of SVG files, entirely from the command line. No UI (user interface) needed, and no front end tools needed.

## Usage Information
To run this application, use the command line to navigate to the directory of the application, install all dependencies (npm i), then type the command node index.js. You will then be taken through a series of questions. Once all questions have been answered properly, a message will display to the command line telling you your logo has been generated. Find your new logo in the newly generated SVG file.

For unit testing instructions, navigate to the Test Instructions section.

## Contribution Guidelines
Open to collaboration, if you choose to do so open an issue and modify any changes you would like to see on a feature branch and wait for approval before merging to the main branch.

## Test Instructions
To run unit testing, open the terminal, and use the command npm run test.






Questions
Have additional questions? Click the links below to reach me through my GitHub account or Email address.

https://github.com/KvnHunt/




