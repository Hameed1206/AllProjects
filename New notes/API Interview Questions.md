API Interview Questions

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*



>>𝗔𝗣𝗜𝘀:

1\) What are the components of an HTTP request?

2\) What is the difference between API and unit testing?

3\) What is an HTTP response?

4\) How we can add validation points in postman?

5\) What do you understand by Server-side validation?

6\) What is 3 tier Architecture?

7\) Difference between webservice \& APIs

8\) What is Rest, Soap \& GraphQL in APIs

9\) What do you test in standalone API?

10\) What do test in 3rd party integrated APIs?



>>𝗣𝗼𝘀𝘁𝗺𝗮𝗻:

1\) When to use collection, environment \& global variables

2\) How to execute a collection E2E

3\) How to validate a API response has correct status code?

4\) What happens when API response returns Form Data instead of Json, how to validate it?

5\) How to setup Basic Auth in Postman?

6\) Where do you store Environment credentials?

7\) How to save a demo response for an API request?

8\) How will you validate an API rqst if VPN is required for it to work?

9\) How do you filter results in a API request using Postman?

10\) How to setup custom headers in Postman?







**Top 10 Rest Assured Functions that every SDET should know!**



1\. given(): The given() method is used to set up the request specification. You can add headers, parameters etc.



Ex: given()

.header("Content-Type", "application/json")

.param("key", "value")



2\. when(): The when() method is used to define the HTTP method (GET, POST, PUT, DELETE) \& the endpoint for the request



Ex: when()

.get("/api/users/2")



3\. then(): method is used to define the response validations \& assertions



Ex: then()

.statusCode(200)

.body("data.id", equalTo(2))



Use Case: Validating the status code \& response body after making a request



4\. statusCode(): The statusCode() method is used to assert the expected HTTP status code of the response



Ex:

then() .statusCode(200) (as can be seen above)



5\. body(): The body() method is used to assert specific parts of the response body



Ex:

then() .body("data.email", equalTo("janet.weaver@reqres.in"))



Use Case:

Validating that the response body if it contains the expected data



6\. log().all(): The log().all() method is used to log the details of the request and response for debugging purposes



Ex:

given() .log().all() when() .get("/api/users/2") .then() .log().all()



7\. header(): The header() method is used to add a single header to the request



Ex:

given() .header("Authorization", "Bearer token")



Use Case:

Including an authorization token in the request header



8\. param(): The param(), or queryParam(), method is used to add query parameters to the request



Example:

given() .param("page", 2)



Use Case:

Sending a query parameter to paginate the results of a GET request



9\. contentType(): The contentType() method is used to set the content type of the request.

Example:

given() .contentType(ContentType.JSON)



Use Case:

Specifying that the request payload is in JSON format



10\. extract():

The extract() method is used to extract parts of the response for further validation or use



Example:

Response response = given() .when() .get("/api/users/2") .then() .extract() .response(); String email = response.path("data.email");



Use Case:

Extracting the response data to perform additional assertions or operations



