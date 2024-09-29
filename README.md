# Real-Time-Chat-Application

Some Features:

1.Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI

2.Authentication & Authorization with JWT

3.Real-time messaging with Socket.io

4.Online user status (Socket.io and React Context)

5.Error handling both on the server and on the client

6.It also saves the chats. Users can view past chats. Because they are saved in the MongoDB database.

-Login Page
![Screenshot 2024-09-29 210040](https://github.com/user-attachments/assets/813c7628-7899-41ac-b0ca-da56bf5e99aa)
-Signup Page
![Screenshot 2024-09-29 210054](https://github.com/user-attachments/assets/8b4ab230-c101-4a7e-b8b8-b37f5086e10d)
-chats
![Screenshot 2024-09-29 210136](https://github.com/user-attachments/assets/845296df-a36a-43e0-92b7-6dce35c0fb24)

## Installation

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
[git clone https://github.com/your-username/chat-app.git](https://github.com/ayushjha-2004/Real-Time-Chat-Application.git)
```
2. Navigate to the Project Directory
```bash

cd chat-app
```
3. Install Server and Client Dependencies
```bash

npm install && cd client && npm install
```
4. Set up Environment Variables
Create a .env file in the root of the project and add the following variables:

```bash

MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
PORT = 5000
NODE_ENV = development
```
5. Start the Development Server
```bash

npm run dev
```
6. Open in Browser
Once the server is running, open your browser and go to:

```bash

http://localhost:3000



