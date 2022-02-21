# Umbreller Seller
![MIT license badge](https://img.shields.io/badge/license-MIT-blue)

## Description

This project is the back end for an e-commerce website. It includes a database of sample items and the api endpoints to perform CRUD operations on that data.

## Table of Contents

[Installation](#installation)

[Usage](#usage)

[Contributing](#contributing)

[License](#license)

[Questions](#questions)

## Installation
You will need to run the **schema.sql** file from the mysql shell. Then use **npm run seed** to seed the database with some sample data. Once you've got your credentials set up in a **.env** file you can run **npm start** to sync the database and start the server.

## Usage
This application is only the back end. Once the server is running use **/api/products**, **/api/categories**, and **/api/tags** with different HTTP requests to interact with the database.

A walk-through video can be found [here](https://drive.google.com/file/d/1ts9E04H3JgFeD3OI8CeZUnR5N_20G1FP/view)

## Contributing
This application uses the following npm packages: 
[dotenv](https://www.npmjs.com/package/dotenv)
[express](https://www.npmjs.com/package/express)
[mysql2](https://www.npmjs.com/package/mysql2)
[sequelize](https://www.npmjs.com/package/sequelize).

## License

### MIT License

Copyright 2022 Colin Bares

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
  
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
  
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Questions
You can check out my other projects on [GitHub](https://www.github.com/soundproofboot). Contact me at  for any further questions.



