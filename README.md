# E-commerce
  
  ![License: gpl](https://img.shields.io/static/v1?label=license&message=gpl&color=green)
  

  ## Description
  This application is the back end application for an e-commerce site. It was built using the latest technologies such as Node.js, Sequelize, Mysql2 and Express. This appilcation creates the API necessary to perform CRUD operations and update the database.

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)

  ## Installation
  To install this application run ```npm i``` to install all the necessary packages.
  
  After installing on the packages, create a .env file in the root level of the folder as shown in the following image.

  ![env file in the root folder](./assets/images/env%20file.png)

  Inside the .env file create the following variables.

  ![variables in the env file](./assets/images/env%20file%20setup.png)

  For ```DB_USER``` set it to the username of your mySQL database that you use. For the ```DB_PASSWORD``` set it to the password of your mySQL database.

  After setting up the .env file. Open a terminal and navigate to the root folder of the project and log into your mysql account and run ```source db/schema.sql```. You should get the following result.
  ![mysql db creation](./assets/images/creating%20db.png)

  Once the database creation is complete, run ```npm run seed``` on the terminal making sure you are still in the root directory of the project. This will create and populate the database tables.

  ## Usage
  To start the application type ```npm start``` in the terminal from the root of the project file.

  ![Application start image](./assets/images/application%20start.png)

  Once the program starts, an API design tool like Insomnia can be used to interact with the database.

  A demonstration video of the application can be found [here](https://drive.google.com/file/d/1gXRhRjEjAcsXV_fE73UtN_qVNpVQqsJZ/view?usp=sharing).
  
  ## License
  This application is available under the GNU General Public License family license.
  
  
  ## Contributing
  Currently there is no way to contribute to this project.

  ## Tests
  This application does not utilize any tests.

  ## Questions
  For any questions about the project, please don't hesitate to reach out.
  * Link to my Github page : [ShawnMaz](https://github.com/ShawnMaz)
  * Email: [shawnmaz@pm.me](mailto:shawnmaz@pm.me)