# E-commerce Back End 

  ## Table of Contents
  1. [Description](#description)
  2. [Installation](#installation)
  3. [Usage](#usage)
  4. [License](#license)
  5. [Contributing](#contributing)
  6. [Questions](#questions)
   
## Description
- The motivation for creating this repository was to help plan the back-end structure of an e-commerce website. 
- This application articulates with a databases to present return organized data to eventually be accessed by front-end developers.
- While creating this application, I was to learn more about the ORM Sequelizer, and continue to get comfortable with the express.js npm.
   
## Installation
To install the project repository, please follow these steps:
1. Clone my repository to your own on your local device.
2. Navigate into the repository root directory.
3. Enter ```npm install ``` into the command line to get access to all the necessary node modules.

## Usage
To get started using this E-commerce database...
1. Set up a .env file and fill in the DB_NAME ('ecommerce_db'), DB_USER & DB_PW (your personal credentials) to link the application to your own MySQL account.
2. Go to the command line. 
3. Enter ```mysql -u root -p``` into the command line, then input your password when prompted.
4. Enter ```source db/schema.sql``` to create and select the database, then ```quit``` to exit the MySQL terminal.
5. Enter ```npm run seed``` to seed the database with the existing categories, products and tags.
6. On the third line from the bottom of the server.js file, change { force: false } to  { force: true }
7. Enter ```npm start``` into the command line to start the server and change code back to { force : false }.
8. Use Insomnia to test routes and add/delete/update data until this application is linked to a front end server.

## License
This project is not licensed.

## Contributing
This project was created based off of starter code provided by the University of Toronto School of Continuing Studies Coding Bootcamp. 

If you would like to contribute to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owner of this repository before making a change. Only respectful engagement with this repository will be tolerated to foster an open and welcome environment.

  ### Pull Request Process
  - Pull requests will be merged upon approval of the repository owner.

## Questions
If you have any questions about this project repository, please feel free to contact its owner.
  #### GitHub: [katiebutler37](https://github.com/katiebutler37)
  #### Email: [katiebutler37@gmail.com](mailto:katiebutler37@gmail.com)

    
