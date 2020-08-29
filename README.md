# Excellent E-Commerce

## Description: 
Excellent E-Commerce is a back-end application that utilizes mysql, and sequelize to create a customizable E-commerce database.

## Usage
### To use Excellent E-Commerce:
1. Clone repository onto a local machine, making sure to run npm i to install dependencies.
2. Open mysql by running `mysql -u root -p` in your terminal.
3. run `source db/schema.sql` to create your database, then run `quit;` to exit mysql.
4. run `npm run seed` to seed information into your database.
5. create a .env file by running `touch .env` in the root directory of your repository, then define `DB_NAME='ecommerce_db'`, `DB_USER='your mysql username'`, and `DB_PW='your mysql password'`.
5. run `npm start` to start your application, then open your program of choice for testing API routes.


**Video demonstration of application (click to be redirected):**
[![Demo](https://i.imgur.com/u90dtTE.png)](https://drive.google.com/file/d/1r7ftTyKByUMJ_WOCjbSrQhOTOQ7MBF7T/view)
