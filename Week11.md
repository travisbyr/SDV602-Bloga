# Week 11

This week our tutor introduced us to http Requests. Here is what I learned:

### Http Requests

For milestone 3 we will be using http requests to request data from a remote database. These http requests will be delivered to an API that will receive and send data according to the URL provided An http request uses a URL to send and retrieve data by reading its contents. Depending on the method used, data can be sent and retrieved in a secure manner that is not visible in the URL.

**POST Method** - This method sends data using the request body, meaning that no data is actually displayed in the URL. This is useful when you are POSTing data such as login/registration forms, as these tend to contain classified data like passwords.

**GET Method** - This method sends data using the body text from the URL. Typically this method is used to 'GET' data, as the data request is visible in the URL. This method would be used when requesting data from a search.

### Application Programming Interface (API)

An API is a software application that enables communication between applications. API's are used to exchange data amongst each other using http requests. An API takes an http request and returns data requested from the http request.

I will be using an API for my project called JSONDrop, where I will be using the get method to retrieve data. An example of what this will look like is shown below:

https://newsimland.com/~todd/JSON/?tok={"tok":"YOUR TOKEN GOES HERE","cmd":{"ALL":"tbl_login"}}

This http requests asks the API to return all the rows within the table 'tbl_login'. The token is a code that each person uniquely has. The command part of the URL is the part that tells the API what to do. The API then uses this information accordingly.



### References

*What is an API? (Application programming interface)*. (n.d.). MuleSoft. Retrieved November 4, 2021, from https://www.mulesoft.com/resources/api/what-is-an-apis