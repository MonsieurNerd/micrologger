# Micro Log

## The goal

The idea is to offer a live tail of a log file, as well as search functionality by regex.

- App must be able to display the full log in a webpage
- App must be able to filter logs using regexp
- App must provide a way to disable/enable live mode
- App should allow to split lines using a regexp/separator and display them
- App should allow to sort on a column 
- App could display some metrics using charts (number of alert / warning ... )


There is two parts for this project

### Server side

Should be based on WebSocket and Node.js.
The file manipulation should be done on this side !
Server should watch a log file (passed as params) 

### Client side

The UI must use VueJS version 3. https://v3.vuejs.org/
For the style you have the plenty choice. 
Keep in mind that the global look & feel of the app will be a strong point of evaluation.

## Notes
Please write the code in ES6 or TS 
You can write some unit test using [JEST](https://jestjs.io/) if you have time...
