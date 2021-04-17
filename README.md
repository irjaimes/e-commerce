# E-commerce Back End

### Table of Contents 
  - [Description](#description)
  - [Installation](#installation)
  - [License](#license)
  - [Contributing](#contributing)
  - [Questions](#questions)

### Description
This E-commerce Back End project uses mysql to configure the database, and uses sequelize to connects to that database. Once the schema and seeds are fed to database, the user can test the data using Isomnia core. API routes can be tested as well as CRUD operations to get, post, put, and delete data from the database. 

### Installation
1. To install all dependencies type `npm i` into the terminal.

### Usage
2. Create a .env file in the root directory. Use the following format to add your username and password to establish the connection to the database through sequelize.

    `DB_NAME = 'ecommerce_db'`

    `DB_USER = ''`

    `DB_PW = '' `

3. In mysql create the database `ecommerce_db` with the schema provided.

4. Type `npm run seed` in the terminal to seed the database.

5. Type `node server` in the terminal to start the server.

6. In Insomnia Core, use the GET, POST, PUT, and DELETE to test CRUD operations with the database information.

### Walkthrough [Video](https://drive.google.com/file/d/10vxPUpXRqn-kXPf5ai5dHqXooljA-q2W/view?usp=sharing)

### Contributing
Idzel Jaimes

### Questions
For any questions, please feel free to contact me.
  * Github Username: [irjaimes](https://github.com/irjaimes/readme-gen)
  * Email : irjaimes@outlook.com
