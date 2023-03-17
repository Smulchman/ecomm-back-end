# E-Commerce-back-end

## Table of Contents:
- [Description](#description)
- [Usage](#usage)
- [Questions](#questions)
- [Credits](#credits)

## Description

This is an operational server back end without a front end utilizing sequelize, mysql, express, and dotenv.

## Usage

You can view a video of the app in use [here](https://drive.google.com/file/d/1Braq8DG3RbQwyNrnuiCkdj2F3E-Sh4xv/view)

To use this app, you will first need to download the repository to your local machine.\
Then use npm i in your console to initialize the node modules required.\
After that you will need to set your own user information for your MySql server in a .env file. The database is named "ecommerce_db".\
The database is linked to get, put, post, and delete requests that you can view in the files contained in the 'routes' folder.\
Make sure you understand what those requests are asking for before you write a front end interaction for them!\
Additionally, you can create and seed the database by first launching your MySql shell then using 'source schema.sql' to create the database or overwrite an existing database of the same name.\
After you've created the database, use the command 'node seeds/index.js' to fill the database with sample data.\
Install insomnia to your local machine and try out all the routes to interact with the database. You can watch the video linked above if you'd like more information as to what using insomnia looks like.

## Questions

GitHub: [Smulchman](https://github.com/Smulchman)\
You can reach me at the following email with any questions regarding this repository:\
Email: Mulcahy.Samuel@gmail.com

## Credits
Created by Sam Mulcahy
I consulted the sequelize docs (linked below) for guidance:\
https://sequelize.org/docs/v6/