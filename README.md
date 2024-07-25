## General info
This project implements authorization logic with access, refresh tokens and email account confirmation.

## Technologies
Project is created with:
* **Express** version: 4.19.2
* **React** version: 18.3.1
* **Typescript** version: 4.9.5

## Project Structure

* `server` - Backend built with Express and MongoDB.
* `client` - Frontend built with React and TypeScript.

## Setup

### 1. Clone the Repository

```
git clone https://github.com/your_username/auth_with_refresh.git
cd auth_with_refresh
```

### 2. Install Dependencies
Navigate to the server folder and install the dependencies:

```
cd server
npm install
```
Then, navigate to the client folder and install the dependencies:
```
cd ../client
npm install
```

### 3. Configure Environment
1. Create a .env file in the server folder and add variables from .env.example file.
2. Make sure the connection with mongodb is established successfully.

### 4. Run the Project
#### 1. Start the Backend.

Navigate to the server folder and start the server:
```
cd server
npm start
```
#### 2. Start the Frontend.

Navigate to the client folder and start the frontend:
```
cd client
npm start
```
## Usage
### 1. Authorization
The project uses access and refresh tokens for user authorization. Routes are defined in server/router/index.js file.
### 2. Email Sending
Email sending is handled through a Gmail SMTP server. Make sure you have the correct credentials.
