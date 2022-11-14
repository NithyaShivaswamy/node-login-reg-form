# node-login-reg-form
A register and login page using NodeJS, Mysql, HTML and CSS

## Prerequisites
Make sure Node is installed
```sh
node -v
npm -v
```

### Setup DB
Make sure Mysql is installed. Create a new database called login_db.
Create a table in login_db with below structure

```sh
create table users(
   ID INT NOT NULL AUTO_INCREMENT,
   name VARCHAR(100) NOT NULL,
   email VARCHAR(100) NOT NULL,
   password VARCHAR(100) NOT NULL,
   PRIMARY KEY ( ID )
);
```

Update the `.env` with below values

```sh
DATABASE = 
DATABASE_HOST = 
DATABASE_USER = 
DATABASE_PASSWORD = 
```
## How to start
```sh
git clone git@github.com:Nithyashivaswamy/node-login-reg-form.git
cd node-login-reg-form
npm install
npm start
```

This is built while learning from [login form](https://blog.logrocket.com/building-simple-login-form-node-js/)