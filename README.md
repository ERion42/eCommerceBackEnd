# eCommerceBackEnd


## Description

Back end with starter code. Configuring a working Express.js API to use Sequelize to interact with a MySQL database.

Currently it is very bare-bones. Most of it works- there are two non-fatal errors when modifying existing records. There is a fatal error when the user tries to delete a product. Other than that it all seems completely functional.

## Table of Contents 

* [Installation](#installation)

* [Usage](#usage)

* [Contributing](#contributing)

* [Tests](#tests)

* [Questions](#questions)

## Installation

To install necessary dependencies, run the following command:

```
npm i
```

## Usage

Once the dependencies are installed, run the following command:

```
npm start
```

From there you'll need to access the local host through a program like Insomnia. At that point it's pretty easy to list all categories, products, and tags. 

To get all entries in a table:
```
GET localhost:3001/api/[categories/tags/products]
```

To get a specific entry in a table:
```
localhost:3001/api/categories/[id]
```


  
## Contributing

Just email me with suggestions or found bugs. Please keep criticism constructive.

## Tests

Currently no tests.

## Questions

If you have any questions about the repo, open an issue or contact me directly at ericrion3000@yahoo.com. You can find more of my work at [ERion42](https://github.com/ERion42/).

