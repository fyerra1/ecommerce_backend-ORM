# Object-Relational Mapping (ORM): E-Commerce Back End

  ## Description

  This a backend application of a sample ecommerce website that utilizes Sequelize and a MYSQL Database 

  ## Video Recording
  [WALK-THROUGH VIDEO](https://drive.google.com/drive/folders/1eBZAD336dVGj7XKMfhvl_BHAKF--iBR-?usp=sharing)

  ## Table of Contents
  #### [Installation](#installation)
  #### [Usage](#usage)
  #### [Contribution](#contribution)
  #### [License](#license)
  #### [Contact](#questions)

  ## Installation

  - On your terminal, create the schema from the MySQL shell by running command 'mysql -u root -p'. Then, enter you credentials and run command 'SOURCE db/schema.sql;'. Be sure to enter 'exit' after schema is created. 
  - Next, seed the database by running command 'npm run seed'.
  - Finally, start the application’s server with command 'npm start'.

  ## Usage
  - GET, POST, PUT, and DELETE test through 'insomnia'
    - Product routes:
      - http://localhost:3001/api/products/
      - http://localhost:3001/api/products/:id
    - Category routes:
      - http://localhost:3001/api/categories/
      - http://localhost:3001/api/categories/:id
    - Tags routes:
      - http://localhost:3001/api/tags/
      - http://localhost:3001/api/tags/:id
  </br>    
  ** categories will not be deleted if they are associated with an available product ** 
    
  ## Contribution

  - Submit a pull request

  ## License

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Questions?

  Github: [fyerra](https://github.com/fyerra)
  E-mail: frankyerra1@gmail.com