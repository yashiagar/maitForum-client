# MAITForum - A discussion Forum - MERN



# Built using
## Front-end
* ReactJS - Frontend framework <br>
* Redux w/ useDispatch & useSelector hooks - For state management <br>
* Redux Thunk - For asynchronous actions <br>
* React Router - For general routing & navigation <br>
* Material-UI w/ lots of CSS customisations - UI library <br>
## Back-end
* Node.js - Runtime environment for JS <br>
* Express.js - Node.js framework, makes process of building APIs easier & faster <br>
* MongoDB - Database to store document-based data <br>
* Mongoose - MongoDB object modeling for Node.js <br>
* Mongoose Unique Validator - Plugin for better error handling of unique fields within Mongoose schema <br>
## Features
* Authentication (login/register with username-password) <br>
* CRUD posts & comments <br>
* Add posts in the form of text or image <br>
* Upvote posts & comments <br>
* Follow option <br>
* Sorting of posts on basis of streams like ece,cse etc. <br>
* Pagination of posts <br>
* Error management to prevent app crashes <br>
* Toast notifications for actions: adding posts, deleting comments etc. <br>
* Loading spinners for relevant fetching processes <br>
* Moderation feature for prevention of abusive langugage <br>
* Responsive UI for all screens <br>

## Env variable:
Create .env file in server directory and add the following: <br>

```
MONGODB_URI = "Your Mongo URI"
```

## Client:
Open client/src/backendUrl.js & change "backend" variable to "http://localhost:3000"
```
cd client
npm install
npm start
```
## Server:
Note: Make sure that you have installed 'nodemon' as global package.
```
cd server
npm install
nodemon start
```
