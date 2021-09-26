# Free Code Camp: Back End Development and APIs Project 4/5
## [Request Header Parser Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/url-shortener-microservice)

This project is the fourth of five projects to be completed for FreeCodeCamp's fifth of six JavaScript certificate: [Back End Development and APIs](https://www.freecodecamp.org/learn/back-end-development-and-apis/#back-end-development-and-apis-projects). A live demo can be found on [Replit](https://replit.com/@john-albright/exercise-tracker-free-code-camp#.replit). The API uses two forms to store exercises performed by a user. The users form stores usernames in a User Mongo DB Atlas model. By making GET requests to the /api/users/ path, one can see a list of all the usernames and ids stored in the User model. One can then enter an exercise into the Exercise Mong DB Atlas model using the second form. The valid ID (one found in the User model), a description, and a duration must be entered for the POST request to /api/users/:_id/exercises to be processed successfully. As an extension of the project, the user can also see a list of all exercises stored in the Exercise model at the api /api/exercises/. Finally, one can access an exercise log of a user by making GET requests to the path /api/users/:_id/logs. The query parameters from, to, and limit can be added to the path to access a specific number of exercises or exercises between specific dates. 
