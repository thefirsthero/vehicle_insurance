# Vehicle Insurance Project
This Insurance Management System project is a website or web application mainly for persons who are willing to buy insurance for their vehicles. Through this website, it will be easier to find a suitable one.
The main intention of building this website is to provide users to choose their budget and the best package for their vehicle. We have tried to maintain all the information about the insurance plan, which is easily understandable to the users and makes it easy to find the plan.
This system helps the user to get a different kind of insurance

# Setup
  * Navigate to `server/src/config/db.config.js`
  * Set your database connection parameters.
  * In the root folder create a file called `.env` and make it look like this:
  * * REACT_APP_HOST=localhost (NB: change to your credentials)
  * * REACT_APP_USER=root (NB: change to your credentials)
  * * REACT_APP_PASS=root (NB: change to your credentials)
  * * REACT_APP_DB=login_register_sys

# Installation
* To install the required node modules for the backend server, navigate to server folder in cmd
  * type `npm install`
* To install the required node modules for the client server, navigate to client folder in cmd
  * type `npm install`

# Starting
* To start the backend server, navigate to server folder in cmd
  * type `npx nodemon server.js`
* To start the client server, navigate to client folder in cmd
  * type `npm start`

# Potential Client npm start issues
delete the `package-lock.json` file<br>
run `npm i`<br>
run `npm update`<br>
run `npm audit fix --force`<br>
run `npm start`
  
  
