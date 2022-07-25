# Password-Generator

This application focuses on the use of Javascript to generate a random, secure password for the user. 

## Getting Started

This project has been deployed to GitHub Pages. To get this project up and running, you can follow the deployment link. Or, download the sources files to use this as a template.


![Password-Generator Demo]

### This project has the following features: 
* A generate button
    * This will send the user a series of prompts to validate choices for password criteria
    * After user choices are complete, the user will get a randomly generated password to copy to their clipboard

* A Copy button 
    * This will copy the randomly generated password to the user's clipboard

### Project Requirements: 
* The user will be prompted to select from the following password criteria: 
    * The generated password must be between 8 and 128 characters
* The user will be prompted to validate: 
    * Password containing uppercase, lowercase, special characters, numbers
    * This will randomly generate a selection or randomly select array data, so math.random and math.floor will need to be used.     
* The application confirms user input and ensures that at least one character type is selected. 
* Once all prompts are complete, the user will be presented with a password fitting the user password criteria.

### Project script includes:
* A variable declaration area 
* An event listener (onclick) called generatePassword
    * This will prompt the user for input between 8-128
    * This variable is changed to an interger using ParseInt()
    * This will confirm that the input is a number and within the range
    * This then uses the input to determine the types of letters or characters used, using an if statement
    * This then assigns values to the variables using arrays for special characters, numbers or the alphabet
* Another variable is created to concatenate these variables into a single password
* A for loop will iterate through the generate prompt until it reaches the number of characters entered by user 
* A password variable then takes the value from the for loop, and converts it to a string
* Then the string populates into the text area for the user
* An event listener (onlick) for copying the string to the user's clipboard confirms the string is on the clipboard

### This project has media Queries for:
* max-width: 980px 
    * Adjusts body and container width
* max-width: 786px
    * Adjusts body and container width
    * Adjusts buttons
* max-width: 690px
    * Adjusts body and container width
    * Adjusts buttons
* max-width: 640px
    * Adjusts buttons to be centered and stacked
* max-width: 500px
    * Adjusts buttons

### Files: 
* One HTML Pages
    * Index.html 
        * Includes basic user input items and buttons with divs and ids
* One CSS Page
    * Styles.css
        * Includes centering and styling for html user input features
        * Includes media queries
* One Javascript Page
        * Includes: 
        * Variables, including arrays and value placeholders
        * Two event listeners
        * Two if/else if statements
        * One function outside of first event listener


## Authors

* **Justin Hollis**

## Acknowledgments

* Special thank you to Jamie Rachael Morris for significant contributions to my understanding of this code - https://github.com/jamierachael







