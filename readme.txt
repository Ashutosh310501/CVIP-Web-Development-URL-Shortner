URL Shortner
Designing a URL shortner service that takes in a valid URL and return a shortened URL,redirecting the user to the previously provided URL.

Also,keep track of total visits/clicks on the URL
Routes
POST/URL-Generates a new short URL and returns the shortened URL in the format example.com/random-id.

GET/:id-redirects the user to the original URL
GET/URL/analytics/:id-Return the clicks for the provided short id.
//To start the application write npm start