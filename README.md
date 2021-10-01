# Acumen QA automation engineer test

This is the repo for the test project for the QA automation tests
The current tech stack being used in the project is 
- Angular 11
- Jest
- Cypress
- SASS/SCSS


## Project setup

Clone the project from 
https://acumen.visualstudio.com/ARMP/_git/Acumen.AutomationTest?version=GBmain
Open it up in an editor of your choice (VS code is reccommended), open the terminal and run ```npm i```
Once that is complete follow the commands below depending on what you want to do

To run the project run 
```npm run start```

To build the project run
```npm run build```

To run unit tests
```npm run test```

To run cypress / automation tests
```npm run cypress```

## Project brief

You have been hired as an automation engineer for this project. They haven’t got any automation in place and are keen to hear your thoughts/approaches on tackling this. Through this exercise you don’t have to write all the tests you would, it is just an important to have it noted down any ideals, blockers or recommendations you have. 

This test project is still small but has some key pieces of functionality, these are 

- Ability to favorite navigation items 
- A users page 
- Ability to see which users are active 
- Ability to search the users by username 
- Ability to delete users 

We want to ensure that this functionality stays consistent so we are looking to add automated testing to the project. 

Other considerations 

- This system could need to support over 10,000 users 
- We do not specify a minimum spec for our users or browser 
- We have multiple clients, so data is likely to change 
