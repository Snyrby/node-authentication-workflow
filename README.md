# node-authentication-workflow

#### Starter
Node project that deals with user authentication, reset password, forgotten password, email verification 

#### Setup

- navigate to authentication-workflow/client
- configure build

```sh
npm run build
```

- navigate to authentication-workflow/server
- install dependencies

```sh
npm install
```

- create .env in the server directory and provide correct values

.env

```js
MONGO_URI=
JWT_SECRET=
JWT_LIFETIME=
SALT=
ETHEREAL_USERNAME=
ETHEREAL_PASSWORD=
```

 - go to https://ethereal.email and click create account for the username and password for .env file

- start the project

```sh
npm start
```