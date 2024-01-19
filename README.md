Steps for execution.
1.Backend Setup

Make mongodb connection by this:
mongoDBURL = "mongodb+srv://<username>:<password>@<name of the DB>.ssobxho.mongodb.net/<add the collection name>?retryWrites=true&w=majority"
change the username and password and also name the database as per needs.

cd backend
npm install
npm run dev

2.Frontend Setup

Open a new terminal and run the following commands to start the frontend server.

cd frontend
npm install
npm run dev


Database Design
Book
Author
Title
Publish Year
Timestamps (Time of creation and time of last update)

API Design
To create a new book in the current existing book collection:
POST(/books)
To get the list of all the books present in the existing book collection:
GET(/books)
To get one particular book from the database:
GET(/books/:id)
To update the information of one particular book:
PUT(/books/:id)
To delete a particular book from the database:
DELETE(/books/:id)

Technologies Used
Full Stack Webdev (MERN)

Frontend:
ReactJS
Tailwind CSS

Backend:
NodeJS
ExpressJS
MongoDB

Challenges Faced
Connecting to the MongoDB
Took lot of time for creating a cluster in the mongodb atlas.

Deploying
Difficulty in deploying at varius cloud platforms.

Connection
Faced a lot of connection issues between the mongodb and the system .


Additional Features
CORS Policy.


Scope for improvement
Can setup user identification like the login,register
Can extend the work much more by adding more books from REST API