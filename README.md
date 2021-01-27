# Web Security & Authorization
This website is a research on the different levels of security that can be applied on the passwords. This project was created when I was taking the course [**The Complete 2021 Web Development Bootcamp**](https://www.udemy.com/course/the-complete-web-development-bootcamp/).

## Level 1
Here the passwords are directly stored into the database. When user tries to login, the password and email is checked in the database and if they are correct user is redirected to the secrets page.

## Level 2
Here the password is encrypted using mongoose-encryption package. The encryption is done using a key SECRET then this encrypted password is stored in the database. When the user tries to login, the password is checked against the decrypted version of password stored in the database.

