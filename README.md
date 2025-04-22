# AirBnB Clone - Web Static

## Overview

This repository contains the first step towards building a full web application: the AirBnB clone. This first step consists of a custom command-line interface for data management and the base classes for the storage of this data. The focus of this repository is on the static web components that will form the front-end of our AirBnB clone.

## Project Structure

- `web_static/` - Directory containing all static web files
  - `styles/` - CSS stylesheets for styling the web pages
  - `images/` - Image assets including logos, icons, and property images
  - `0-index.html`, `1-index.html`, etc. - Progressive HTML files showing the development process

## Command Interpreter

### How to Start It

```bash
$ ./console.py
(hbnb) 

Execute

How to Use It
The command interpreter allows you to manage the objects of the project:

Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc...
Do operations on objects (count, compute stats, etc...)
Update attributes of an object
Destroy an object
Examples
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

Execute

Web Static
The web_static part of this project focuses on creating the HTML and CSS for the application. The goal is to:

Create simple HTML static pages
Style the HTML with CSS
Create template layouts using HTML and CSS
HTML Files
Each HTML file in the web_static directory represents a step in the development process:

0-index.html: Basic HTML page with inline styling
1-index.html: HTML page with styling in the head
2-index.html: HTML page with external CSS files
And so on...
CSS Files
The CSS files provide styling for the HTML pages, organized in the styles directory:

common.css: Common styles for all pages
header.css: Styles for the header section
footer.css: Styles for the footer section
places.css: Styles for the places/properties section
Learning Objectives
What is HTML and how to create an HTML page
What is CSS and how to add style to an element
What is the DOM and how to access it
How to select HTML elements in JavaScript
What are the different APIs available in JavaScript
How to manipulate CSS from JavaScript
How to work with the browser loading process
Requirements
All files should end with a new line
A README.md file at the root of the folder
HTML and CSS code should be W3C compliant
All CSS files should be in the styles folder
Images should be in the images folder
You are not allowed to use !important and id (#... in the CSS file)
You are not allowed to use tags img, embed and iframe
You are not allowed to use Javascript
Your code should be W3C compliant and validate with W3C-Validator
Usage
To view the web pages, simply open any of the HTML files in a web browser.
