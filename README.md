
# EchoChat

## Description
EchoChat is a versatile chat platform that allows users to engage in group and personal conversations seamlessly. This project leverages the power of Chat Engine and React to provide a robust and interactive chatting experience.

## Tech Stack Used
- **MongoDB:** NoSQL database for storing user data and project information.
- **Express.js:** Backend web application framework running on Node.js.
- **React:** Frontend library for building the user interface.
- **Node.js:** JavaScript runtime environment for executing server-side JavaScript code.
- **Socket.IO:** Real-time communication for chat functionality.

## Features
- Real-time Chat: Engage in real-time conversations with others on the platform.
- Group Chats: Create and join group chats to collaborate and communicate with multiple users simultaneously.
- Personal Chats: Initiate and participate in one-on-one conversations for more private interactions.
- Media Sharing: Share images and videos seamlessly within the chat.

## Installation and Setup

1. **Prerequisites:**
   - Node.js (v14 or later)
   - npm (v6 or later)

2. **Clone the Repository:**
   ```sh
   git clone [https://github.com/Nikhil-IITG/KritiDevelopmentPS.git](https://github.com/Nikhil-IITG/EchoChat.git)
   cd EchoChat
   ```

3. **Backend Setup:**
   - Navigate to the backend directory.
   - Install dependencies:
     ```sh
     cd backend
     npm install
     ```
   - Start the server:
     ```sh
     npm start
     ```

4. **Frontend Setup:**
   - Navigate to the frontend directory.
   - Install dependencies:
     ```sh
     cd frontend
     npm install
     ```
   - Start the React app:
     ```sh
     npm start
     ```
   - The application should now be running on `http://localhost:3000`.

5. **Environment Variables:**
   Make a file named .env in the backend folder, it's content should be:
   ```sh
    CHAT_ENGINE_PROJECT_ID = your_chat_engine_project_id
    CHAT_ENGINE_PRIVATE_KEY = your_chat_engine_private_key
    ```
   Make a file named .env in the frontend folder, it's content should be:
   ```sh
    REACT_APP_CHAT_ENGINE_PROJECT_ID=your_chat_engine_project_id
    ```
    One can get all of these values from https://chatengine.io/.



## Contributing
We welcome contributions to EchoChat! If you have any ideas, suggestions, or issues, please open a new issue or submit a pull request.

## Steps to Contribute
- Fork the repository.
- Create a new branch (git checkout -b feature/your-feature).
- Make your changes.
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature/your-feature).
- Open a pull request.
