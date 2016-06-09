# Web Development Template

#### This is a lightweight repository to deploy a basic project at the beginning of each Epicodus pair and solo project. It is meant to save time and support clean builds. Current as of June 1, 2016

#### By Kevin VanEvery, Cory Olson, and Patrick Lipscomb

## Description

This repository contains the following folders and files.  They can be used to support a basic project template for the beginning of each of your projects.

Specs:
-This program should translate all the Roman numerals to numbers.
  -Example Input: "VIXV"
  -Example Output: "5","1","10","5" <br>

-This program should add the number that is in the last place to the total.
  -Example Input: "5"
  -Example Output: "5" <br>

-If the number in the second-to-last placeholder is greater than or equal to the number in the last place, the program should add this to the total.
  -Example Input: "VI"
  -Example Output: "6" <br>

-If the number in the second-to-last placeholder is less than the number in the last place, the program should subtract this from the total.
  -Example Input: "IV"
  -Example Output: "4" <br>

-If the number in the third-to-last placeholder is less than the total of the last two numbers, the program should subtract this from the total.
  -Example Input: "IVV"
  -Example Output: "9"

-If the number in the third-to-last placeholder is greater than the total of the last two numbers, the program should add this to the total.
  -Example Input: "VVI"
  -Example Output: "11 " 

## Setup/Installation Requirements

To create your own template repository on github

* Clone the github repository using the git clone command from /Desktop
* Create a new repository on github to keep your template
* Using git remote add pair the clone on your desktop with your new repository
* Add, commit, and push, and then you'll have your own copy of the template to do with as you wish

To install this repository into a new project each time, first

* Clone the github repository using the git clone command from /Desktop
* Move the .pairs folder to the /users folder (one level up from /Desktop)
* Create a new folder in the Desktop with your project name
* Copy and paste the entire contents of the cloned /bootstrap-jquery-project-template into your new folder (this should not include the .pairs file)
* Move into your new folder and initialize git as normal
* Congrats! You now have a new repo based on this template

Some **DONT'S**

* Don't just rename the cloned git repository - that will mess up future commits.  Do the copy/paste
* If you're using a bootstrap template, don't replace the <head> tag.  Only change the <body> tag.  The templates include code at the top and bottom that bring in js and css we're already including and a bunch we don't use.  If you call a js or css file twice, it causes problems.  
## Known Bugs

None.  But we haven't really tested much, so if you find anything, let us know and we'll fix it and update the repo.  

## Support and contact details

Come by during class if you have questions.

## Technologies Used

* Bootstrap
* JQuery

### License

Licensed under the MIT License

Copyright (c) 2016 **Epicodus Pair Projects**
