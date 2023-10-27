# TODO LIST WITH REACT,EXPRESS AND MYSQL

## Requirement : Node.js,React.js,XAMPP(8.2)

### Installation project - Backend

- install Node.js
- install XAMPP 8.2. If you already have one, run XAMPP Control Panel
- start Apache and MySQL
- extract folder from zip
- run vscode and open the folder that has been extracted from the zip
- open a terminal, then navigate to the folder backend `cd backend`
- add node modules `npm install`
- create db `npx sequelize db:create`
- migrate table `npx sequelize db:migrate`
- `npm run start` or `npm run start-dev` (using nodemon)
- open Postman and import Postman Collection from folder postman-collection
- to test API from Postman, can be seen from the import results

### Installation project - Frontend

- open new terminal from vscode which has been opened
- navigate directory to folder backend `cd frontend`
- add node modules `npm install`
- run react app `npm run start`

### Note: Must run both in terminal and dont forget to run XAMPP. It's a good idea to carry out the installation according to the guide above and run the backend first and then the frontend

Thanks