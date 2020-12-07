download or take git clone

Run the following commands


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