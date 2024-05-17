# Permalist-Todo-List-Project
Permalist is a straightforward web-based to-do list app developed using Node.js, Express.js, PostgreSQL, and EJS. It enables users to create, modify, and remove to-do list items.

# Features
This applications is built using CRUD principles. In this project we can: 
- Add new tasks.
- Edit current tasks.
- Delete tasks.
- View all tasks.

# Setting up the project
1. Clown the current repository:
   [https://github.com/SaikrishnaSamudrala3/Permalist-Todo-List-Project]
2. Install the necessary dependencies:
   - npm install
   - install express ejs axios
   - node index.js
3. Database setup
   - Set up a PostgreSQL database named permalist.
   - Execute the queries in queries.sql to create the table and add sample data.
     # psql -U your-username -d your-database-name -a -f queries.sql
     Replace your-username and your-database-name with your PostgreSQL username and database name.
4. Running the applications
   - npm start
   - Open your browser and visit http://localhost:3000 to use Permalist to do list.
# Functions and Usage
  - On the homepage, you'll see a list of current tasks.
  - To add a new task, type the title in the input field and click "Add".
  - To edit a task, click the edit icon next to it, change the title, and click "Save".
  - To delete a task, click the delete icon next to it.
