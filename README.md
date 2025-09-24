Setup a Mongoose Schema and Insert Records
📌 Project Overview

This project demonstrates how to create a Mongoose schema in a Node.js application and insert multiple records into a MongoDB database.

🚀 Getting Started
1. Install Mongoose

Initialize a Node.js project and install Mongoose:

npm init -y
npm install mongoose

2. Create Schema and Model

Connect to MongoDB (e.g., schoolDB).

Define a Student schema with fields:

name (String, required)

rollNo (Number, required, unique)

branch (String)

year (Number)

email (String)

Create a Student model from the schema.

3. Insert Records

Use insertMany() to add multiple student records to the database.

4. Run the project

Start MongoDB service (if local) and execute:

node app.js


Now check the terminal for:

✅ Connected to MongoDB

✅ Students inserted successfully

📂 Project Structure
mongoose-schema/
 ├── app.js
 ├── package.json
 └── README.md

✅ Output
![WhatsApp Image 2025-09-19 at 09 39 49_61ee7fe2](https://github.com/user-attachments/assets/dd46d2bf-9ff2-42b8-b9a0-9fdc873f39fc)
![WhatsApp Image 2025-09-19 at 09 39 50_3b4848b6](https://github.com/user-attachments/assets/0de0927d-8890-44e1-9336-6eec9503302e)

