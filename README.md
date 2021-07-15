# CAPSTONE API
## POST - REGISTER DEVELOPER
$~$
> ### https://app-api-devjobs.herokuapp.com/register
>
> $~$
### linkedin and adress are not required
$~$
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
$~$
## POST- Login DEVELOPER
$~$
> ### https://app-api-devjobs.herokuapp.com/login
>
> $~$
### Body json:
```
{
  "email": "italo@mail.com"
  "password": "123456"
}
```
---
$~$
## POST - Register COMPANY
$~$
> ### https://app-api-devjobs.herokuapp.com/companies
>
> $~$
### Body json:
```
{
  "companyName": "Kenzie",
  "email": "kenzie@kenzie.com"
  "password": "123456"
}
```
---
$~$
## POST - Login COMPANY
$~$
> ### https://app-api-devjobs.herokuapp.com/companies
>
> $~$
### Body json:
```
{
  "companyName": "Kenzie",
  "email": "kenzie@kenzie.com"
  "password": "123456"
}
```
---
$~$
## GET - get a list of all messages
$~$
> ### https://app-api-devjobs.herokuapp.com/messages
---
$~$
## GET - get user's message
> ### https://app-api-devjobs.herokuapp.com/users/${userId}/messages
---
$~$
## POST - post a new message
$~$
> ### https://app-api-devjobs.herokuapp.com/messages
>
> $~$
### Body json:
```
{
  "userId": 1,
  "companyEmail": "esparta@esparta.com",
  "message": "Lorem ipsum sdkvjbsdv"
}
```
---
$~$
## DELETE - Delete a message
$~$
> ### https://app-api-devjobs.herokuapp.com/messages/`${message_id}`
---
$~$
## POST - post education resume information
$~$
> ### https://app-api-devjobs.herokuapp.com/education
>
> $~$
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
$~$
## POST - post experience resume information
$~$
> ### https://app-api-devjobs.herokuapp.com/experience
>
> $~$
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
$~$
## POST - post objective resume information
$~$
> ### https://app-api-devjobs.herokuapp.com/users/`${userId}`
>
> $~$
### Body json:
```
{
  "objective": ""
}
```
---
$~$
## POST - post other skills resume information
$~$
> ### https://app-api-devjobs.herokuapp.com/otherSkills
>
> $~$
### Body json:
```
{
  "userId": 1,
  "level": "",
  "description": ""
}
```
---
$~$
## POST - post tech skills resume information
$~$
> ### https://app-api-devjobs.herokuapp.com/techSkills
>
> $~$
### Body json:
```
{
  "userId": 1,
  "level": "",
  "description": ""
}
```
---