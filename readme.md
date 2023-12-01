# BE Assignment

## How to run the project
Run the following commands in the root directory of the project
```
npm install
npm start
```
The server will start on port 3001

## Tests
Run the following command in the root directory of the project
```
npm test
```
Make sure to run the server before running the tests




## API Endpoints

### 1. Get all the users
```
POST /api/users/register
```
#### Request Body
```
{
    "name": "John Doe",
    "email": "randomemail@gmail.com",
    "password": "123456"
}
```
#### Response
```
{
    "success": true,
    "message": "User registered successfully"
}
```

### 2. Login
```
POST /api/users/login
```
#### Request Body
```
{
    "email": "randomemail@gmail.com",
    "password": "123456"
}
```

### 3. Logout
```
GET /api/users/logout
```
