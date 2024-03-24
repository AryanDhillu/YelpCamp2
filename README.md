# About the Project

YelpCamp provides users with a comprehensive platform tailored for exploring and reviewing campsites and outdoor recreational areas. Upon signing up and logging in, users gain access to a wealth of features designed to enhance their camping experience. They can seamlessly browse through a diverse range of listings, each accompanied by detailed descriptions and vibrant images, facilitating informed decision-making. With the ability to read and leave reviews, users contribute to a dynamic community where experiences are shared and insights are valued. The interactive nature of the platform allows users to upload their own images, enriching the database with diverse perspectives and visuals. Features such as commenting and liking reviews foster engagement among users, creating a sense of camaraderie and shared passion for outdoor adventures. Furthermore, the platform offers personalization options, enabling users to save favorite campsites or receive tailored recommendations based on their preferences and past activity. With its user-friendly interface prioritizing usability, YelpCamp serves as not only a tool for discovering new camping destinations but also a hub for community interaction, experience-sharing, and a celebration of the great outdoors.

### To run project

Need to have installed node, mongoDB, Gitbash.

To set up the project, begin by navigating to the project directory and ensuring you have the required environment variables configured, as specified in the `.env` file. Then, execute `npm install` in the command line to install all necessary dependencies.

Next, create a database. Move into the `seeds` directory and run `node index.js` to populate your MongoDB database with initial data. You can verify the database creation and data insertion using either the MongoDB shell or MongoDB Compass.

Once the database is set up, return to the main directory and start the server by running `node app.js`. This will launch the server on port 8080, allowing you to access the partially functional site via your web browser.

For full functionality, users need to register an account on the site. After registration, retrieve the `userID` from the MongoDB database using the MongoDB shell. Paste this `userID` into the appropriate location in the code, specifically in line 29 of the `index.js` file.

After updating the `userID`, stop the server, re-run `index.js`, and then start the server again with `app.js` using `node`. This will enable you to access the fully functional backend-based site at port 8080.
