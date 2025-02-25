## Project Name: FlowDone-server

### A brief description: 
- FlowDone is a task management application that enables users to efficiently add, edit, delete, and reorder tasks using an intuitive drag-and-drop interface. The tasks are categorized into three sections: To-Do, In Progress, and Done, ensuring seamless workflow organization.
 


---
  


### Dependencies:
- cookie-parser: ^1.4.7,
- cors : ^2.8.5,
- dotenv : ^16.4.7,
- express : ^4.21.2,
- jsonwebtoken : ^9.0.2,
- mongodb : ^6.12.0

### How to run on local machine?

1. Open your terminal or command prompt.

2. Use the git clone command followed by the repository URL:-  git clone 'repository-url'

- Replace 'repository-url' with the actual URL of the Git repository you want to clone.

3. To run the project: Navigate to the project directory:- cd 'directory-name' 

4. Run 'npm install' to install project dependencies.

5. Environment setup:Create a '.env' file and put your firebase environment variable there. Save the following variable:
- DB_USER='YOUR_DB_USER'
- DB_PASS='YOUR_DB_PASS'
- SECRET_KEY='YOUR_JWT_TOKEN_SECRET'

6. Run 'npm run dev' to run the project locally.


<hr/>
