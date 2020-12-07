download or take git clone

Run the following commands

Create databse in mongodb
==========================

goto mongo db folder -> (C:\Program Files\MongoDB\Server\4.2\bin)

start mongodb service
	> net start mongodb
	> mongo
	
list db list
	> show dbs
	
	> use node_db
	> show dbs
	
Mongodb service should be in running condition.!
===============================================


	>npm install

	>nodemon start 

you can check authentication in following urls

=================================================

POST http://localhost:3000/user/signup

post data { "name" : "test name", "email": "user@mail.com", "country" : "india", "mobile_no" : "9876543251", "password":"abc123" }

Response { "message": "User created successfully" }

=================================================

POST http://localhost:3000/user/login

Post data {"email": "user@mail.com", "password" : "abc123"}

Response { "message": "Login successful", "token": "Auth_token" }

=================================================

POST http://localhost:3000/user/authenticate

Post data Pass auth token through bearer token