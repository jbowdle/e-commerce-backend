# E-Commerce Backend

## Description
This program is an e-commerce backend. It can be used to track product data by categorizing and associating tags with it. It uses MySQL and Sequelize to manage the database.

## Installation
To install, run:
```
npm i
```

## Usage
To use, set up the mysql database:
```
mysql -u root -p

SOURCE db/schema.sql;

quit
```

Seed the database with example data:
```
node seeds/index.js
```

Then to start the server run:
```
npm start
```

The backend can now be used by making get, post, put, and delete requests to the api/categories, api/products, and api/tags endpoints.

## Walkthrough Video
(Walkthrough Link)[https://drive.google.com/file/d/1ptGcSLuQKfXQLcUVezFVkYryBfHoeRIK/view]