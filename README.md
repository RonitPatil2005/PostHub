# PostHub
PostHub is a simple CRUD (Create, Read, Update, Delete) web application built using Node.js, Express, and EJS, without using any database.
It is designed purely for learning RESTful routing and CRUD operations.

✨ Features
📄 View all posts
➕ Create a new post
👀 View post details
✏️ Edit a post
🗑 Delete a post

🔁 RESTful routing
❌ No database (in-memory data)
🛠 Tech Stack
  - Node.js
  - Express.js
  - EJS (Embedded JavaScript Templates)
  - UUID (for unique post IDs)
  - Method-Override
  - HTML & CSS

📦 Installation & Setup
1️⃣ Clone the Repository
2️⃣ Navigate to Project Folder
3️⃣ Install Dependencies - npm install
4️⃣ Start the Server - node index.js
5️⃣ Open in Browser - http:/localhost:3000/posts

📌 Routes Overview
Method	Route	Description
GET	/posts	Show all posts
GET	/posts/new	Create new post form
POST	/posts	Add new post
GET	/posts/:id	Show single post
GET	/posts/:id/edit	Edit post form
PATCH	/posts/:id	Update post
DELETE	/posts/:id	Delete post

📂 Project Purpose
 This project was built to:
     - Understand CRUD operations
     - Learn RESTful routing
     - Practice Express + EJS
     - Use method-override
     - Prepare for database-based MERN projects




"Learn CRUD & REST the right way — without database complexity."
