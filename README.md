# 465Gilmore

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

The main distinction between frontend development and the SPA is that the latter is intended for frequent modification and contains quick, easy, and accessible capabilities that bring value to the company and refresh the front page's content. We accomplish this using Angular, a framework designed expressly for this. Express, a different framework built on node.js that is incredibly lightweight and enables us to create dynamic content for the customer side, is used for the frontend portion. Both frameworks depend significantly on javascript.
Why did the backend use a NoSQL MongoDB database?

The NoSQL MongoDB database was utilized for the backend because it is so simple to use; rather than setting up a whole SQL database, we can quickly define a schema using mongoose and then simply toss it at the database, and it works.

Functionality
How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON is a set of properly specified parameters that, when combined, constitute an object that javascript can read and edit. JSON serves as a container for our data in this instance, and we utilize it as a message to instruct the website on what to load. The backend SPA may build new JSON objects with a POST API request for whatever precise database schema is necessary, and the frontend reads them with a GET API request.

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

In order to decrease the amount of hardcoded HTML and make things more modular, handlebars were the primary code restructuring technique employed in this project. For instance, we might abstract that and refer to the handlebars, which would then retrieve the data necessary to populate the components from the database, rather than hardcoding every aspect of a trip on the Travlr page. This is advantageous since it allows us to dynamically change material without shutting down the server and greatly reduces the likelihood of errors.

Testing
Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

I conducted my testing by making extensive use of the Postman software and doing POST/GET/ETC using the API on the express server. This worked extremely well, and after making sure the API was operational, I could start the SPA backend and test the use of the API for actions like adding, editing, and deleting flights. We invoked a simple function to verify if the user was logged in to ensure that damaging commands were not displayed or available until signed in when I installed the security solution and had usernames/passwords. This is how I made the application secure.

Reflection
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

Even though I have to confess that I don't think node packages should be relied upon much, this project was challenging. Due to previous security breaches, I'm a little hesitant to utilize them. But because of how quickly web design has developed, using node packages is now essentially necessary in order to integrate contemporary functionality, which is a strange position to be in. However, getting the mongoDB components to function locally was similarly difficult; this was the first time I had a firm grasp of how to create a RESTful API.
