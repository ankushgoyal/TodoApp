TodoApp
=======
1) The todo items should have endpoints that provide the following functionalities:

- Get

- Delete

- Save

- Update

- Mark as done/undone

- Search

Todo items have a title, a body, and a boolean value to check if it has been done or not.

{

   "title" : "",

   "body" : "",

   "done" false

}

2) In this first version you can store the items in-memory in a static class. Storing them in MongoDB is a plus.

3) For the search functionality, you can use ElasticSearch and specifically https://searchbox.io which has a free plan. The search endpoint should search the query in the title and in the body of the todo item, giving an higher ranking to the matches found in the title.

4) When an API is marked as done, you can use Twilio to send an sms like:

"Cleaning the house" task has been marked as done.

Twilio also has a free plan that you can use.

There is no rush, it would be cool if you could finish it in a week. This project allows me to understand:

1) Your understanding of RESTful APIs and HTTP. A proper API should use HTTP status codes, and be compliant with the HTTP best practices.

2) Your attitude in learning new tools. Jersey it's pretty easy to use. You can create a Maven project if you prefer so it will be easier to download the dependencies and run the API. You can run the application in any container (we're using Tomcat, but it's up to you).

3) If you implement the Mongo datastore, your understanding it getting started with a simple key/value store and your attitude in learning new tools.

4) Being able to consume a third party API like Twilio, and integrate it into the app.

5) Your ability to write modular, clean, understandable and beautiful Java code.
