# Outdoor Adventure Meetup

Outdoor Adventure Meetup is a vibrant web application designed to bring together enthusiasts of outdoor activities. 
From seasoned explorers to newcomers, our platform offers a unique space for individuals to discover, share, and participate in outdoor adventures. 
Whether it’s local hiking, mountain biking, or international expeditions, there’s something for everyone here. 

## Features
1. **User Profiles:** Create and manage your personal profile to track your events and RSVPs.
2. **Event Management:** Users can create, discover, and RSVP to events. Each event includes detailed information like date, time, and location.
3. **Community Engagement:** Engage with a community that shares your enthusiasm for the outdoors. Share experiences and connect with fellow adventurers.
4. **Responsive Design:** Enjoy a seamless experience across all devices, ensuring you can access the platform wherever you go.

## Technologies
1. **Node.js:** The core runtime environment for running JavaScript on the server side.
2. **Express:** A web application framework for Node.js, used to build web applications and APIs.
3. **MongoDB:** A NoSQL database used to store application data.
4. **EJS:** A templating engine used in the views folder for generating HTML markup dynamically.
5. **bcrypt:** A library to help you hash passwords securely.
6. **Git:** Version control system to handle the project's development across multiple stages and versions.
7. **npm:** Node package manager for handling project dependencies.
8. **HTML/CSS/JavaScript:** Used for structuring, styling, and functionality of the public-facing pages.
9. **JSON:** Data interchange format used within package.json and possibly for APIs.
10. **Middleware Functions:** Custom or third-party middleware used within Express for various backend functionalities like logging, request processing, etc.

## Structure Description
1. **Models:** Contains data models for the application, interacting with databases or other data sources.
2. **Views:** Holds template files for rendering HTML.
3. **Controllers:** Manages the application logic, linking the models and views.
4. **Routes:** Defines the URLs the web application handles and links them to specific controller functions.
5. **Public:** Stores static files that are directly accessible via the web browser.
6. **Middlewares:** Implements functions that have access to the HTTP request and response objects and the next middleware function in the application’s request-response cycle.

## Setup
_Prerequisites_
1. Node.js - Ensure you have Node.js installed on your machine. It can be downloaded from Node.js official website.
2. MongoDB - Make sure MongoDB is installed and running on your machine. Instructions can be found on the MongoDB official website.

_Installation_
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies uisng terminal: Enter **_npm install_**
4. Replace 'your-database-name' and 'your-secret-key' with your database name and a secret key in the app.js file: DB_URI=mongodb://localhost:27017/your-database-name
SESSION_SECRET=your-secret-key
5. Run the application using terminal:Enter **_node app.js_** or **_node app_**
6. Open your browser and go to **_http://localhost:3000_** to view the application.

_Additional Notes_
1. Ensure MongoDB is running on your system to connect to the database successfully.
2. If you encounter any npm errors during installation, try clearing the npm cache with **_npm cache clean_** and reinstall the dependencies.

## Website Images
1. Home Page:
<img width="1512" alt="Screenshot 2024-05-07 at 12 29 31 PM" src="https://github.com/priyam-02/Outdoor_Adventure_Meetup/assets/108848788/d1984d48-1904-4990-902a-d5f33c7870ed">
<img width="1512" alt="Screenshot 2024-05-07 at 12 29 42 PM" src="https://github.com/priyam-02/Outdoor_Adventure_Meetup/assets/108848788/2a8c3147-93dc-41b9-99c2-950aebc21c50">



