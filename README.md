# ECommerce-Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## This program is an ECommerce back end server and database. The user can search the database, create database items, update items, and delete items. This project uses starter code from bootcamp. 

Watch a demo video [here](https://drive.google.com/file/d/1k5FPZnqpPLWpmHPDnVVGjnAuYCnT6BWy/view?usp=sharing)

## Table of Contents:
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [License](#license)
- [Contributing](#contributing)
- [Testing](#tests)
- [Questions](#questions)
## Installation 
Clone the repository from GitHub onto your machine in a local folder. This program will require Node.js and MySQL. Install node.js: [Installation Guide](https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs). Install MySQL: [Installation Guide](https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide). From the root of the project folder do an npm (Node Package Manager) install to get the package dependencies (type `npm install` on the command line).   
## Usage 
Step one: From the command line enter into MySQL using the command `mysql -u root -p` and then enter your password. Step two: Enter `source db/schema.sql` to initialize the daatabase. Exit MySQL. Step three: Seed the database using the command: `node seeds/index.js`. Step four: Enter `npm start` to start the server. Step five: Use Insomnia to search all or individual categories, products, and tags and to create, update, or delete items. 

![Screenshot](./assets/Screen%20Shot%202022-07-27%20at%2010.09.02%20AM%20Small.jpeg)
![Screenshot](./assets/Screen%20Shot%202022-07-27%20at%2010.09.31%20AM%20Small.jpeg)
![Screenshot](./assets/Screen%20Shot%202022-07-27%20at%2010.09.45%20AM%20Small.jpeg)
![Screenshot](./assets/Screen%20Shot%202022-07-27%20at%2010.10.08%20AM%20Small.jpeg)
![Screenshot](./assets/Screen%20Shot%202022-07-27%20at%2010.10.34%20AM%20Small.jpeg)

## Technologies
- Javascript
- [Express](https://expressjs.com/)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://sequelize.org/)
## License 
&copy; 2022 by Amy McCabe. 
This project is licensed under the MIT license.
https://opensource.org/licenses/MIT  
## Contributing 
To contribute to this project please make a new issue or pull request in the GitHub repo. 
## Tests 
Use Insomnia, Postman, or other program to test.
## Questions 
Contact me at: [mcca0168@umn.edu](mailto:mcca0168@umn.edu) or [GitHub](https://github.com/McAmy2001/)
