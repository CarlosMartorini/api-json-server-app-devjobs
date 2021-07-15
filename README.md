# CAPSTONE API
## POST - REGISTER DEVELOPER
<br></br>
> ### https://app-api-devjobs.herokuapp.com/register
<br></br>
### linkedin and adress are not required
<br></br>
### Body json:
```
{
  "email": "italo@mail.com",
  "password": "123456",
  "fisrtName": "italo",
  "lastName": "Cello",
  "birthDate": "12/03/1994",
  "linkedinProfile": "",
  "address": "",
  "phone": "99999999"
}
```
---
<br></br>
## POST- Login DEVELOPER
<br></br>
> ### https://app-api-devjobs.herokuapp.com/login
<br></br>
### Body json:
```
{
  "email": "italo@mail.com"
  "password": "123456"
}
```
---
<br></br>
## POST - Register COMPANY
<br></br>
> ### https://app-api-devjobs.herokuapp.com/companies
<br></br>
### Body json:
```
{
  "companyName": "Kenzie",
  "email": "kenzie@kenzie.com"
  "password": "123456"
}
```
---
<br></br>
## POST - Login COMPANY
<br></br>
> ### https://app-api-devjobs.herokuapp.com/companies
<br></br>
### Body json:
```
{
  "companyName": "Kenzie",
  "email": "kenzie@kenzie.com"
  "password": "123456"
}
```
---
<br></br>
## GET - get a list of all messages
<br></br>
> ### https://app-api-devjobs.herokuapp.com/messages
---
<br></br>
## GET - get user's message
> ### https://app-api-devjobs.herokuapp.com/users/${userId}/messages
---
<br></br>
## POST - post a new message
<br></br>
> ### https://app-api-devjobs.herokuapp.com/messages
<br></br>
### Body json:
```
{
  "userId": 1,
  "companyEmail": "esparta@esparta.com",
  "message": "Lorem ipsum sdkvjbsdv"
}
```
---
<br></br>
## DELETE - Delete a message
<br></br>
> ### https://app-api-devjobs.herokuapp.com/messages/`${message_id}`
---
<br></br>
## POST - post education resume information
<br></br>
> ### https://app-api-devjobs.herokuapp.com/education
<br></br>
### Body json:
```
{
  "userId": 1,
  "degree": "",
  "school": "",
  "dateFrom": "",
  "dateTo": "",
  "description": ""
}
```
---
<br></br>
## POST - post experience resume information
<br></br>
> ### https://app-api-devjobs.herokuapp.com/experience
<br></br>
### Body json:
```
{
  "userId": 1,
  "role": "",
  "company": "",
  "dateFrom": "",
  "dateTo": "",
  "description": ""
}
```
---
<br></br>
## POST - post objective resume information
<br></br>
> ### https://app-api-devjobs.herokuapp.com/users/`${userId}`
<br></br>
### Body json:
```
{
  "objective": ""
}
```
---
<br></br>
## POST - post other skills resume information
<br></br>
> ### https://app-api-devjobs.herokuapp.com/otherSkills
<br></br>
### Body json:
```
{
  "userId": 1,
  "level": "",
  "description": ""
}
```
---
<br></br>
## POST - post tech skills resume information
<br></br>
> ### https://app-api-devjobs.herokuapp.com/techSkills
<br></br>
### Body json:
```
{
  "userId": 1,
  "level": "",
  "description": ""
}
```
---

















