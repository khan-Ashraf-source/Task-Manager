# Mini Project – Task Notes App

A mini Node.js + Express application that lets you create, view, and edit text-based tasks.  
Currently, tasks are stored as individual text files, but the project will be upgraded to MongoDB for database storage.  
The app uses EJS templates for rendering and Tailwind CSS for styling.

---

## Features
- Create new tasks with a title and description  
- View all saved tasks  
- Rename tasks  
- Styled with Tailwind CSS  
- File-based storage (soon MongoDB)

---

## Project Structure
mini-project/
├── src/
│   ├── server.js             # Entry point (starts Express app)
│   ├── app.js                # Express app config (middleware, routes)
│   ├── config/
│   │   └── db.js             # MongoDB connection setup (Mongoose)
│   ├── models/
│   │   └── Task.js           # Mongoose schema/model for tasks
│   ├── routes/
│   │   └── tasks.js          # All task-related routes (CRUD)
│   ├── controllers/
│   │   └── taskController.js # Logic for handling requests
│   ├── views/                # EJS templates
│   │   ├── index.ejs
│   │   ├── show.ejs
│   │   └── edit.ejs
│   └── public/               # Static files
│       ├── stylesheets/
│       │   └── style.css
│       ├── javascripts/
│       │   └── script.js
│       └── images/
├── .gitignore
├── package.json
├── README.md

---

Tech Stack
- Node.js
- Express
- EJS
- Tailwind CSS (via CDN)
- MongoDB (coming soon)

---

Future Improvements
- Replace file storage with MongoDB
- Add delete functionality
- Add error handling and validation
- Flash messages for success/error
- Deploy online (Render/Heroku/Railway)
