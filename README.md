🚀 Getting Started
1. Create a new Node.js project

Create a folder (e.g., node-mongo), initialize npm, and install the required packages:

mkdir node-mongo
cd node-mongo
npm init -y
npm install express mongoose

2. Setup MongoDB

Use either a local MongoDB server or MongoDB Atlas cluster:

Local Connection:
mongodb://127.0.0.1:27017/mydb

Atlas Connection:
mongodb+srv://<username>:<password>@cluster0.mongodb.net/mydb

3. Run the project

Start the MongoDB service (for local):

mongod


Run the server:

node app.js


Now open your browser or Postman at the suggested URL (usually http://localhost:3000). You can test:

POST /users to add a user

GET /users to retrieve all users

📂 Project Structure
node-mongo/
 ├── app.js
 ├── package.json
 └── README.md

✅ Output

When the app runs successfully, the terminal will display:

✅ Connected to MongoDB
🚀 Server running at http://localhost:3000/

![WhatsApp Image 2025-09-19 at 09 36 59_85fa76b1](https://github.com/user-attachments/assets/0e3c49de-bf95-4e57-94b8-2ce9c6580dac)

![WhatsApp Image 2025-09-19 at 09 36 59_9e3a8a21](https://github.com/user-attachments/assets/e602b212-7d74-4732-9c70-52a3bf1dfca9)
