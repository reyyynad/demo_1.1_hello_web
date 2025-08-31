Demo #1
# Running Your First Full-Stack Web Application

## Overview
This demo will get you running a complete web application using Node.js and Express. You'll see how frontend and backend work together to create a functional web app.

## What You'll Run
A simple "Hello World" web application featuring:
- Node.js Express server with basic routes
- HTML/CSS frontend
- Simple API endpoint
- Basic client-server communication

## Prerequisites
- Node.js 14+ installed on your computer
- Git installed on your computer

## Instructions

## Step 1: Clone the Project

1. Clone the project repository:
   ```bash
   git clone https://github.com/Web-Engineering-KFUPM/web_course_main
   cd demos/Chapter\ 1/1.1\ hello\ web/
   ```

## Step 2: Install Dependencies

1. Install the required packages:
   ```bash
   npm install
   ```

## Step 3: Run the Application

1. Start the Node.js server:
   ```bash
   npm start
   ```
   
   Or run directly with:
   ```bash
   node app.js
   ```

2. Open your web browser and go to: `http://localhost:3000`

3. You should see your web application running!

## Step 4: Customize with Your Name

1. Open the file `app.js` in your text editor
2. Find the line that says:
   ```javascript
   res.json({ message: 'Hello from the server!' });
   ```
3. Change it to include your name:
   ```javascript
   res.json({ message: 'Hello [YOUR_NAME]!' });
   ```
4. Save the file and restart the server (Ctrl+C, then `npm start` again)
5. Refresh your browser and click the button to see your personalized message!

## What You're Running

Your web application has:

### Backend (Node.js Server):
- **Express Framework**: Handles HTTP requests and responses
- **Routes**: Define different URLs your app responds to
- **API Endpoints**: `/api/hello` returns JSON data
- **Static File Serving**: Serves HTML, CSS, and JavaScript files

### Frontend (HTML/CSS/JavaScript):
- **HTML Structure**: Simple page with button and content
- **CSS Styling**: Clean, centered design
- **JavaScript**: Handles API calls and displays responses

## Understanding the Flow

1. **User visits the page**: Browser requests `http://localhost:3000/`
2. **Server responds**: Express serves the `index.html` file from the public directory
3. **User clicks button**: JavaScript sends request to `/api/hello` endpoint
4. **Server processes**: Node.js code returns JSON response
5. **Response sent back**: Server sends JSON data
6. **Page updates**: JavaScript displays the API response

## Troubleshooting

- **Port already in use**: Change the PORT variable in `app.js`
- **Module not found**: Make sure you ran `npm install`
- **Page not loading**: Check that your server is running and visit the correct URL
- **API not working**: Check browser console for JavaScript errors

## Project Structure

Your project looks like this:
```
[PROJECT_FOLDER]/
├── node_modules/         # Dependencies (created by npm)
├── public/
│   └── index.html       # Your HTML file
├── app.js               # Your Node.js server
├── package.json         # Project configuration
└── package-lock.json    # Dependency lock file
```

Congratulations! You've successfully run your first full-stack web application with Node.js! 🎉

