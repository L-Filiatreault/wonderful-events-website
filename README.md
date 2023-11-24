# Wonderful Events :partying_face:
This website was the final project of my Web Programming II course and was done within a group. It was a culmination of about 2 months work, where we combined our personal assignments and built a website that uses MVC (Model-View-Controller) architecture and CRUD operations to add, read, update and delete data from the website. It uses Docker to store information in the database. 

*Objectives of this project*
To build a transactional web application which demonstrates:
- CRUD operations with MVC
- MySQL database backing up the model
- Using Handlebars to render views
- Must include user login capability with associated authentication and sessions 

This point of this website is to help people plan their events better. Be it through adding and editing the guests, music and meals designed for the party.

It offers the user many options for planning their event:

1. Creating an event.
2. Adding songs that will be played at the event.
3. Adding guests that will coming to that event.
4. Adding what meals those guests will be eating at the event.
5. Editing all the information above.
6. Choosing between previously created events to see information about them.
7. Store all of the information on a database.

All of this functionality and more (such as selecting between French and English as the display language) is packaged in a fun and user-friendly design.

This website is coded using Node.js and Handlebars.

## Get Started Working On Files
### Add all NPM packages
`npm i express express-handlebars express-list-routes init jest mysql2 pino pino-caller pino-http pino-pretty supertest validator bcrypt cookie-parser uuid`

### Using Docker container

Create it:
`docker run -p 4242:3306 --name wonderfulEventsContainer -e MYSQL_ROOT_PASSWORD=tatltuae -e MYSQL_DATABASE=wonderful_events_db -d mysql:5.7`

Run it:
`docker container exec -it wonderfulEventsContainer`

Enter MySQL:
`mysql -u root -p`

Enter password:
`tatltuae`
