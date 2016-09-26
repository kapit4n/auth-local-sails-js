# Sail with sails-permissions

a [Sails](http://sailsjs.org) application

## Install
sails lift

## Run
http://localhost:1337/auth/local

POST request(Using postman)
{
    "identifier": "admin@example.com",
    "password": "admin1234"
}

## response
{
    "createdBy": 1,
    "owner": 1,
    "username": "admin",
    "email": "admin@example.com",
    "model": 2,
    "createdAt": "2016-09-26T17:47:09.047Z",
    "updatedAt": "2016-09-26T17:47:09.319Z",
    "id": 1,
    "gravatarUrl": "https://gravatar.com/avatar/e64c7d89f26bd1972efa854d13d7dd61"
}

## Ref
#### http://sailsjs.org/documentation/concepts/policies/sails-passport
#### https://www.npmjs.com/package/sails-permissions#1-configure-sailsrc
