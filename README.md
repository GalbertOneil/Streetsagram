# Find Streetstagram on Surge!
http://infamous-trick.surge.sh

# Screenshots
![Imgur](https://i.imgur.com/yI5l9UQ.png)
![Imgur](https://i.imgur.com/WV9EVt8.png)

# Streetstagram
Streetstagram builds community by creating a platform for artists to share their work, and for individuals to engage with
each other by sharing images of streetscapes.

Streetstagram is a fullstack application that uses React.js, Express, Sequelize and Node.js. 

Streetstagram communicates with AWS cloud storage to host image urls.

## Installation and Set up
The Streetstagram database is deployed to [Heroku](https://streetstagram.herokuapp.com/).

### Create the Database

1. `createdb streetstagram_db`
1. `node scripts/resetDb.js`
1. `node scripts/seedDb.js`

### Install packages
`npm install --save express aws-sdk bluebird fs file-type multiparty cors morgan`

### Run the server

1. `node server.js`

### Run the app

1. `cd client`
1. `npm start`


## User Stories
- As an artist I want to find street shots so that I can be inspired.  
- As a tourist I want to find street shots so that I can find fun places to go.
- As a model/photographer I want to find street shots so that I can locate good shooting locations.
- As a user I want to be able to have a medium to share my hobbies / interests.
- As an artist  I want to be able to share my art to gain a wider audience.
- As a millennial, I want to post cool photos of my city to gain social clout with my friends.
