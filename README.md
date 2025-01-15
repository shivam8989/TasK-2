# TasK-2
 chat application
 # Chat Application

This is a real-time chat application built using WebSocket for instant messaging, allowing users to sign up, log in, and communicate with each other. The application stores user data and chat messages in a database and retrieves old messages for seamless conversations.

## Features

- **User Authentication:**
  - Users can sign up and log in to the chat application.
  
- **User List:**
  - A collapsible left-side menu displays all registered users.

- **Chat Interface:**
  - The logged-in user can select any other user from the menu to initiate a chat.
  - Old messages are retrieved and displayed in the chat interface.
  
- **Real-time Communication:**
  - The chat application uses WebSocket to enable real-time messaging between users.
  
- **Database Integration:**
  - All user data (username, password, etc.) and chat messages are stored in a database for persistence.

- **User-friendly Interface:**
  - A simple, intuitive, and functional user interface for seamless interaction.

## Technologies Used

- **Backend:**
  - Node.js
  - Express.js
  - WebSocket (for real-time communication)
  - MongoDB (for database storage)

- **Frontend:**
  - HTML5
  - CSS3
  - JavaScript (Vanilla or React.js)
  
- **Authentication:**
  - JWT (JSON Web Tokens)

## Installation

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js (v16.x or later)
- MongoDB (or use MongoDB Atlas for cloud hosting)

### Clone the repository

```bash
git clone https://github.com/your-username/chat-application.git
cd chat-application

