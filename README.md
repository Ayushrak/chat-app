# 💬 Chat App 🚀  
A **MERN Stack** real-time chat application with **Socket.io** for instant messaging.  

## 📌 Features  
- 🔐 **User Authentication** (Signup/Login)  
- 💬 **Real-time Chat** with WebSockets  
- 📜 **One-on-One & Group Chat Support**  
- 🛑 **Online/Offline User Status**  
- 🎨 **Responsive UI using React & Tailwind CSS**  
- 🌐 **RESTful API with Express & MongoDB**  
- 🔔 **Typing Indicators & Notifications**  
- 🗂 **Media & File Sharing**  

## 🛠️ Tech Stack  
- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **WebSockets:** Socket.io  
- **Authentication:** JWT  

## 🚀 Installation & Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/Ayushrak/chat-app.git
cd chat-app
```
### 2️⃣ Install Dependencies
### Frontend Setup
```
cd frontend
npm install
npm start
```
### Backend Setup
```
cd backend
npm install
npm start
```
###3️⃣ Environment Variables
Create a .env file in the backend directory and add the following:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
SOCKET_PORT=5001
```

### 4️⃣ Run the Application
```
Frontend: Runs on http://localhost:3000
Backend: Runs on http://localhost:5000
WebSockets: Runs on http://localhost:5001
```
### 🛠 API Endpoints
```Endpoint	Method	Description
/api/users	GET	Get all users
/api/auth/signup	POST	Register a new user
/api/auth/login	POST	User login
/api/messages	GET	Get chat history
/api/messages	POST	Send a new message
```
### 🤝 Contributing
Contributions are welcome! Fork this repo, make your changes, and submit a pull request.

### 📄 License
This project is open-source and available under the MIT License.

