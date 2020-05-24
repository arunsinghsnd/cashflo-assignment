# This  stateless microservice in Nodejs, with two major functionalities
 * Authentication,
 * Image Thumbnail Generation ,


## Setup

To get up and running: 

**1.** Clone the repo.
```
git clone https://github.com/arunsinghsnd/cashflo-assignment.git
```

**2.**  Setup the application by installing its dependencies with
```
npm install
```

**3.**  The app gets up and running on port 3000 with ```npm start```.


## Protected Endpoint 
 The following endpoint is protected with The JWT obtained in the “Login” endpoint must be attached  to each request. If the JWT is missing or invalid, these endpoints should reject the request. 


## Testing the API routes.

Since this is mostly an API with post and patch requests, testing will be done with [Postman](https://www.getpostman.com/)

### Authentication
This is a mock authentication so you can pass in any username or password to login.
 

 ### Image Thumbnail Generation
This request contains a public image URL. It downloads the image, resizes to 50x50 pixels, and returns the resulting thumbnail.
 
## Built With

 * [Node.js](https://nodejs.org)
 * [Express](https://expressjs.com/)
 