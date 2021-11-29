###### Reddish - A Reddit Clone - MERN
#### Built using
########### Front-end
>ReactJS - Frontend framework
>Redux w/ useDispatch & useSelector hooks - For state management
>Redux Thunk - For asynchronous actions
>React Router - For general routing & navigation
>Formik - For flexible forms
>Material-UI w/ lots of CSS customisations - UI library
##Back-end
>Node.js - Runtime environment for JS
>Express.js - Node.js framework, makes process of building APIs easier & faster
>MongoDB - Database to store document-based data
>Mongoose - MongoDB object modeling for Node.js
>Mongoose Unique Validator - Plugin for better error handling of unique fields within Mongoose schema
##Features
>Authentication (login/register with username-password)
>CRUD posts & comments
>Add posts in the form of text or image
>Upvote posts & comments
>Follow option
>Sorting of posts on basis of streams like ece,cse etc.
>Pagination of posts
>Error management to prevent app crashes
>Toast notifications for actions: adding posts, deleting comments etc.
>Loading spinners for relevant fetching processes
>Moderation feature for prevention of abusive langugage
>Responsive UI for all screens
##Usage
Notes:

>For image API, make account at cloudinary.com & get API keys from account dashboard.

##Env variable:
Create .env file in server directory and add the following:

```MONGODB_URI = "Your Mongo URI"
```

##Client:
Open client/src/backendUrl.js & change "backend" variable to "http://localhost:3000"
```
cd client
npm install
npm start
```
##Server:
Note: Make sure that you have installed 'nodemon' as global package.
```
cd server
npm install
npm run dev
```
