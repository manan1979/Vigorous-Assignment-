Setting Up the MERN Application:

1. Database Connection:

Go to MongoDB and log in.
Create a cluster and get the connection link.
Copy the link, username, and password.

2. Configure .env file:

In the project folder, create a file named ".env".
Inside the file, add: DATABASE="your connection link here"
Running the Application:

1 . Run the Client:

Open the terminal and navigate to the "client" folder using the cd command.
Type npm start in the terminal.
The application will start, and you can view it on localhost:3000.

2. Run the Server:

Open another terminal and go to the project folder.
Type nodemon start in the terminal.
The server will start on localhost:8080 and connect to the database.
Remember to update the password if needed.
Now, run the application and check it out!
