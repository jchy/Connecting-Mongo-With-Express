# Connection-Mongo-With-Express
Displaying users, pagination, delete, post and patch request has been implemented in this project

Steps to run this project
Step 1.
- Clone this repo on your local system using following url :~
```js
  https://github.com/jchy/Connecting-Mongo-With-Express.git
```
Step 2.
- Now navigate inside the < ConnectingMongoDbToExpress > folder 

Step 3.
- Now run the following command
```js
  npm install
```

Step 4.
- Open the mongo or mongosh terminal and run the mongo databse named "masai"

Step 5.
- Make sure that your databse < masai > have < users > collection 

Step 6.
- Now in your terminal ( preferably VS Code Terminal ) run the following command :~
```js
  npm run start
```
Step 7.
- Now go to postmane and make a GET request at the following URL to get all users with their data :~
```js
  http://localhost:5001/users
```

Step 8.
- To get a specific user make a GET request at the following url :~
```js
  http://localhost:5001/users/code/pw_009
```

Step 9.
- To make a PATCH request got to follwoing usr :~
```js
  http://localhost:5001/users/< user_id >
```

Step 10.
- To delete a user make a delete request at the following url with user_id :~
```js
  http://localhost:5001/users/ < user_id >
```
