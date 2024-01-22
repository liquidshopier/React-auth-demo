## Simple React Router v4 Auth example

### Description

This is a simple example of authentication using React with a json-server backend.  The application presents a login page as well as both public and protected routes.  The main purpose of this application is to demonstrate a basic login flow and how to restrict routes or change data based on the logged in user.

This app stores a list of games with the following restrictions:

1.  Anonymous users are allowed to view the home, about, and login pages.
2.	Normal users are also allowed to access the games route.
3.  Admin users are allowed to create or delete games.

If you are not familiar with React Router v4, I recommend you take a look at some of the samples in their [documentation](https://reacttraining.com/react-router/web/guides/quick-start).

### Running locally
```
git clone git@github.com:jeremyjung/react-auth-demo.git
cd react-auth-demo
npm install
cd client
npm install
cd ..
npm start
```

