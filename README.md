# Node-Authentication-API

API for registering users with mongodb and authentication using JWT (json web token). This app uses passport and passport-jwt and uses jwt strategy

##Version
```
1.0.0
```

##Usage
```
npm install
```
```
npm start
```

#Endpoints
```
POST /users/register
```
```
POST /users/authenticate //Gives back a token
```
```
GET /users/profile //needs json web token to authorize
```
