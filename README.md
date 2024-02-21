# Chatbot Application

This project is a Node.js application that integrates Google's Dialogflow for natural language processing (NLP) and MongoDB for data storage. The application is built using Express.js and includes user authentication and authorization mechanisms using JSON Web Tokens (JWT).

## Features
Dialogflow Integration: The application interacts with Google's Dialogflow platform to handle natural language processing. It receives incoming POST requests from Dialogflow, processes them based on defined intents, and sends appropriate responses.
MongoDB Integration: User information, trouble tickets, and issue status are stored and retrieved from a MongoDB database. The application queries the database to authenticate users, generate trouble tickets, and manage issue status.
Rich Responses: The application can send rich responses to Dialogflow with lists of options for users to choose from, enhancing the user experience.
Troubleshooting and Issue Tracking: Users can report issues and receive generated trouble ticket numbers for tracking purposes. The application logs issue details, including user information, issue type, and status, in the MongoDB database.
