# Micro Log
**iXblue Technical Test**
<br>
## The goal

The idea is to provide a live tail of a log file, with a search functionality by regex.

- App must be able to display the full log in a webpage
- App must be able to filter logs using regexp
- App must provide a way to disable/enable live mode
- App should allow to split lines/columns using a regexp/separator and display them
- App should allow to sort on a column
- App could display some metrics using charts (number of alert / warning...)


There are two parts for this project:

### Server side

Should be based on WebSocket and Node.js.

The file manipulation should be done on this side!

Server should watch a log file (passed as params).

### Client side

The UI must use VueJS version 3 with composition API.

For the style you have the plenty choice.

Keep in mind that the global look & feel of the app will be a strong point of evaluation.

## Notes
Please write the code in modern JavaScript or TypeScript.

You can write some unit tests and/or front-end tests (with Cypress) if you have time...

You must provide a README file to explain how your app is built.

You can explain in README what could have been done with more time.
