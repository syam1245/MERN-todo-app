
**MERN Stack To-Do App**

Description:
---
**Overview:**
This project is a full-stack web application developed using the MERN (MongoDB, Express, React, Node.js) stack. It serves as a To-Do list application, allowing users to add, view, and delete tasks. This documentation provides insights into the project's structure, functionality, and setup.

**Features:**
- **Create Tasks:** Users can add new tasks with descriptions.
- **View Tasks:** View all tasks in a user-friendly interface.
- **Delete Tasks:** Remove completed or unnecessary tasks.
- **Responsive Design:** The application is designed to work seamlessly on both desktop and mobile devices.

**Technical Stack:**
- **Frontend:** Built using React for dynamic user interfaces.
- **Backend:** Node.js and Express for server-side logic.
- **Database:** MongoDB for data storage.
- **API:** RESTful API for CRUD operations.
- **Deployment:** Easily deployable to cloud platforms like Heroku or AWS.

**Usage:**
- Clone the repository.
- Set up the MongoDB database and configure the connection in the `.env` file.
- Run `npm install` to install dependencies.
- Use `npm start` to launch the development server.
- Access the app in your browser.

**Technical Documentation:**
- The project structure follows the MERN architecture.
- `/client`: Frontend code using React.
- `/server`: Backend code using Node.js and Express.
- `/models`: MongoDB schema for the "To-Do" item.
- `/routes`: API routes for CRUD operations.
- `/views`: React components for the frontend.
- `.env`: Configure your MongoDB connection here.
- `index.js`: Entry point for the server.

This project was developed following the guide from [DevGenius](https://blog.devgenius.io/how-to-get-started-with-the-mern-stack-the-easy-way-b9758fe45956), providing a smooth introduction to MERN stack development. You can find the full code on this GitHub repository.

Technical Documentation:
---
**Project Structure:**

- **/client:** Contains the frontend code developed in React.
- **/server:** Houses the backend logic created using Node.js and Express.
- **/models:** Defines the MongoDB schema for the "To-Do" item.
- **/routes:** Contains the API routes responsible for CRUD operations.
- **/views:** Consists of React components used in the frontend.
- **.env:** Configure your MongoDB connection details in this file.
- **index.js:** Acts as the entry point for the server.

**Installation:**

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Configure MongoDB:
   - Create a MongoDB database.
   - Set the connection string in the `.env` file.

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```


