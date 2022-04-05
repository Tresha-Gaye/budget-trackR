# Budget Tracker Starter Code

## Description

This application allows offline access and functionality of a budget tracker, allowing users to add expenses dn deposits to their budgert with or without a connection. 

You may view the deployed application by [clicking this link](https://drive.google.com/file/d/1OWYnzRi8q8v4JxNK0U3tAXJoHFUC7n1o/view).


## Technologies

- The application uses IndebDB and a service worker for offline functionality.
- Express.js server to test the service worker.
- Web manifest let's users know what they are installing and how it should look on their screen
- 

## Criteria

**User Story**

AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

**Acceptance Criteria**

GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

## Accomplishments and Challenges

The application successfully connects to the database and syncs the Mongoose models. 
- The API GET routes for thoughts and users displays JSON data for each route.
- the API POST, PUT, and DELETE routes create, update and delete users, their  friends, their associated thoughts, add and remove thoughts associated reactions in the database

**Below are a screenshots of the app showing the functionality:**

Below are images from Insomnia, displaying data:  
<br />
![Add-friend](./public/assets/images/add-friend.jpg)  
<br />
![Add-thought](./public/assets/images/add-thought.jpg)  
<br />
![All-users](./public/assets/images/get-users.jpg) 

## Contributing

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## Credits

**The following resources were used to complete this project:**
1. UCONN Coding Bootcamp's modules on NoSQL/MongoDB
2. [Mongoose](https://mongoosejs.com/docs/index.html) Documentation 
3. [MongoDB Schema Validation](https://www.mongodb.com/docs/manual/core/schema-validation/) Documentation 
4. [MDN Web Docs on Javascript Date object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) Documentation 

## License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

