URL Shortener Backend - edited
We have build this project using java, spring boot and Mongo 

Shorten URLs: We take those lengthy links and make them short.
Store in MongoDB: The short links and their original URLs  are stored safely in MongoDB.

Steps to run the application:
Clone the Repo: Grab a copy of our code by running this in your terminal:
shell
Copy code
git clone https://github.com/Srithanvi28/url-shortener_backend.git

Install Stuff: Go into the project folder and install the IDE with Maven:
shell
Copy code
cd url-shortener-backend
mvn install

MongoDB Setup: We have to install Mongo DB. Update the connection info in application.properties.

Run the Show: Start the application with:

shell
Copy code
mvn spring-boot:run
How to Use
Now that everything's up, you can use our URL shortener service through some simple API calls.

API Endpoints
Shorten URL: POST /api/shorten - Give us a long URL in the request, and we'll give you a shortened one.
Redirect: GET /{shortCode} - Enter a short code, and we'll redirect you to the original URL.
For more details about using the API, check out our API documentation.

This is Backend code. WE will configure with front end to run the application 



THANK YOU.
