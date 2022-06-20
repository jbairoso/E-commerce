# E-commerce
## User Story
AS A manager at an internet retail company</br>
I WANT a back end for my e-commerce website that uses the latest technologies</br>
SO THAT my company can compete with other e-commerce companies</br>
## Acceptance Criteria
GIVEN a functional Express.js API</br>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file</br>
THEN I am able to connect to a database using Sequelize</br>
WHEN I enter schema and seed commands</br>
THEN a development database is created and is seeded with test data</br>
WHEN I enter the command to invoke the application</br>
THEN my server is started and the Sequelize models are synced to the MySQL database</br>
WHEN I open API GET routes in Insomnia for categories, products, or tags</br>
THEN the data for each of these routes is displayed in a formatted JSON</br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia</br>
THEN I am able to successfully create, update, and delete data in my database</br>

## How to:
*Clone my github repo: https://github.com/jbairoso/E-commerce </br>
*In the terminal enter 'mysql -u root -p" enter your password</br>
*Input source db/schema.sql</br>
*Open up a new terminal</br>
*Input npm run seed</br>
*Input npm start</br>
*Use the Insomnia app to see all the requests for GET, PUT, POST, DELETE</br>
## Visuals
GET all categories, products, and tags</br>
![ScreenShot](/gifs/GET%20all%20categories%2C%20products%2C%20%26%20tags.gif)</br>
GET categories, products, and tags by ID</br>
![ScreenShot](/gifs/GET%20all%20categories%2C%20products%2C%20%26%20tags%20by%20ID.gif)</br>
PUT, POST, DELETE video </br>
https://drive.google.com/file/d/1kJ30dc3X8kmugtXORLsBlYcoxEy7ZYkU/view

