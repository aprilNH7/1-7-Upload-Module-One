# 1-7-Upload-Module-One

# Overview
In this course, you will be building a full stack application using the MEAN stack, which stands for MongoDB, Express, Angular, and Node.js. This README will guide you through the initial setup and development process of the Travlr Getaways project.

# Prerequisites
Before starting, ensure you have the following installed:

Node.js
Node Package Manager (NPM)
Additionally, review the following materials:

Project Guidelines and Rubric
Travlr Getaways’ software requirements and wireframe (provided in the Project Guidelines and Rubric)
Travlr Getaways HTML mockup pages (available in the travlr.zip file in the Supporting Materials)

# Setup Instructions

# Step 1: Install Node.js and NPM
Download and install Node.js and NPM from Node.js official website.

# Step 2: Review Project Guidelines and Software Requirements
Thoroughly review the project guidelines, rubric, and software requirements to understand the scope and objectives of the project.

# Step 3: Review HTML Mockup Pages
Download the travlr.zip file from the Supporting Materials.
Unzip the file and open index.html in your web browser to review the mockup pages.

# Step 4: Clone GitHub Repository
Clone your GitHub repository to a local directory:
bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project directory:
bash
Copy code
cd your-repo-name
Update the .gitignore file as needed to exclude unnecessary files from being tracked.

# Step 5: Create Module1 Branch
Create a new branch for the Module 1 work:

bash
Copy code
git checkout -b module1
Development Instructions

# Step 6: Build the Website with Node.js and Express
Initialize a new Node.js project:
bash
Copy code
npm init -y
Install Express:
bash
Copy code
npm install express
Create the following directory structure:
java
Copy code
├── public
│   ├── css
│   ├── js
│   ├── images
│   └── index.html
├── routes
├── views
├── app.js
├── package.json
└── .gitignore

# Step 7: Serve Static HTML Content
In app.js, set up the Express server to serve static content from the public directory:
javascript
Copy code
const express = require('express');
const app = express();

app.use(express.static('public'));

const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
    console.log(`Server is running on port ${PORT}`);
});
Place your static HTML, CSS, JavaScript, and images into the appropriate folders inside the public directory.

# Step 8: Test the Setup
Start the Express server:
bash
Copy code
node app.js
Open your web browser and navigate to http://localhost:3000 to verify that the static HTML content is being correctly served.

# Step 9: Verify HTML Content
Test the application to ensure it displays the HTML content properly in the browser. Make sure the navigation, links, and any other static elements are functioning as expected.

# Conclusion
By following these steps, you will set up a working shell of the customer-facing web application using the MEAN stack. Continue referring to the Full Stack Guide provided in the course materials for detailed instructions and further development.

Happy coding!

# Supporting Materials

Module One Full Stack Guide (link to the specific guide provided by the course)
Travlr Getaways Project Guidelines and Rubric (link to the project guidelines and rubric)
Travlr.zip (link to download the HTML mockup pages)
