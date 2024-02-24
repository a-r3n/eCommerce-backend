# eCommerce-backend
A backend management system for an eCommerce website 


https://drive.google.com/file/d/1DWJic6eDA4KQPSmqiQsZPhLUe-MqZt6U/view

https://github.com/a-r3n/eCommerce-backend 


## Description

This application uses express.js and mySQL to give eCommerce website owners an easy way to update, change and manage their eCommerce listings. 

Simply using an application like Insomnia, website owners can add new product lines, delete product lines and ensure each product listing has the correct information associated with it. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To install the application, the user must first download the application from the GitHub respository: https://github.com/a-r3n/eCommerce-backend 

The user should also have mySQL and Insomnia installed on their computer. 

## Usage

To run the application, ensure mySQL is running. 

Then set up the application in an integrated terminal such as VS Code. Run 'npm install', 'node seeds/index.js' and 'node server.js' to ensure the application is properly set up with on your local host. 

Then on an application like Apple's terminal get to the correct folder and run mySQL. Ensure the application is sourcing the correct file (in this case /db/schema.sql) and the right database (in this case 'ecommerce_db')

Then in Insomnia, run a simple GET function to ensure the application is set up and working correctly. 

As a test, run GET: http://localhost:3001/api/categories

If it is working correctly, you should see a screen like below: 

![alt text](assets/Module-13-Challenge-Screenshot.png)


We have created a walkthrough video of the application in use, which can be viewed here: https://drive.google.com/file/d/1DWJic6eDA4KQPSmqiQsZPhLUe-MqZt6U/view

## Credits

This application couldn't have been made without the help of a number of contributors. 

Firstly, to the University of Sydney Coding Bootcamp team for the Starter Code. The code can be accessed at this GitHub repository: https://github.com/coding-boot-camp/fantastic-umbrella

Secondly, to all the people that have contributed to the applications that allowed this project to run - mySQL, Sequelise, Express and Insomnia - thank you. 

## License

This application has been built under an MIT License. 

For more information on the license and how this project can be used, please refer to the License file in this application's GitHub repository. 