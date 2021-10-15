# saloon-test

Clone the project
Enter command =>  npm i

create database and update the db configuration in config file

open index.js
Uncomment line number 9 => await sequelize.sync({ force: true })

run the project => nodemon index.js
it will create all the tables inside database
comment the line number 9 in index.js =>  // await sequelize.sync({ force: true })
save the file

open http://localhost:4000/saloon-docs in your browser to see the API documentation 
