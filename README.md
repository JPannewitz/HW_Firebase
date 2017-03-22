# HW_Firebase
Homework assignment #7

## Live Link 
 - https://jpannewitz.github.io/HW_Firebase/

## Description on how to use the app
This is a simple train schedule application that incorporates Firebase to host arrival and departure data. This app retrieves and manipulates user input with Moment.js, and then a table provide up-to-date information about various trains, i.e. their arrival times and how many minutes remain until they arrive at their station.

## Requirements

-When adding trains, administrators should be able to submit the following:
    -Train Name
    -Destination 
    -First Train Time -- in military time
    -Frequency -- in minutes
 -Code this app with Moment.js to calculate when the next train will arrive; this should be relative to the current time.
 -Users from many different machines must be able to view same train times, and the data will still be available once you refresh the browser

## Technologies Used

- HTML, Bootstrap & CSS for the layout
- Javascript/JQuery to dynamically update HTML
- Firebase to store user input 

## Code Explaination
- First created basic HTML with Bootstrap CSS that could be called upon in the Javascript file
- There are two main containers: a table that displays train data and a form that takes user input for train information
- Used JQuery to dynamically update HTML to display the user input as well as calculated times from Moment.js
- Used persistence of Firebase to store user input for later retrieval

-------------