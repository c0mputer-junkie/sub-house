# sub-house
a mapping app that allows users to find temporary housing in their local area

** Technologies ** : React, Express, Sql, Node

* This project was bootstrapped with Create React App
  https://github.com/facebookincubator/create-react-app

## MySQL Database setup
Download `Sequel Pro` (https://sequelpro.com)
Open `Sequel Pro` and enter the following to establish a connection:

    ```
    Host: 127.0.0.1
    Username: root
    ```
Create a new database named `sub-house`
Within the `sub-house` database, create one table: `listings`

    - In `listings` table, add these columns: `title`, `price`, `location`, `link`

 ### Application Setup:

1. Go onto your desktop and then clone this repo to your local machine

    `cd desktop` and `git clone https://github.com/c0mputer-junkie/sub-house.git`

2. Go into that project folder

    `cd sub-house`


3. Install all dependencies

    `npm i `
    or

    `yarn`

6. Run `yarn start` or `npm start` (this will run both the client and server)

### running express
1. install nodemon
    `npm install --save-dev nodemon`
2. to Run nodemon
    `nodemon run server.js`

### Current features:
- User can view current listing in local area 
- User can view more description about listing via craigslist

### Later features:
- User can login
- User can search current listing in local area  
- User can create their own listing
- calendar - to book dates
- rate and review - user and host can rate and review each other
- payment link - where use can make payments
- Save multiple maps of different cities/countries
  - Filter
  - pet friendly
- User can like their and save their favorite listings
    - shared room
    - private house

![subhouseimage](public/images/subhouseimage.png)
