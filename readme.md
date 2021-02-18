## SQL Injection Tutorial

# DON'T USE JAVASCRIPT VARIABLES TO BUILD YOUR SQL STRINGS, use your sql lib's input sanitation

## Non Malicious tasks:

### Create a user (Do not enter any real information!!)

POST https://coldbabka.com/victim/user
Req Body Params: username, password, ssn, bankAcct

### read your user's info

GET https://coldbabka.com/victim/user
Req Query Params: username, password, ssn, bankAcct

### update your user

PUT https://coldbabka.com/victim/user
Req Body Params: username, password, ssn, bankAcct

## Malicious tasks using sql injection

##### Figure out how to read all info for all users

##### Figure out how to update one user without their password

##### Figure out how to update all users with one request
