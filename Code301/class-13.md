# Read: Class (13) CRUD

## There is some important question we should ask us about CRUD

---
<br>

**1-In your own words, describe what each group of status code represents:**

_*100’s = In the header part there is a problem before they start sending the body (failure)._

_*200’s = code that tells the client that its request was accepted at the time of sending(success)._

_*300’s =redirection codes tell the client that the resource they are requesting isn’t available and it's maybe temporary or permanent. (failure)_

_*400’s = client error codes about invalid requests several causes to this like timeout, wrong URI, missing authentication because there is sending incorrect input._

_*500’s = It's server error codes unreachable servers behind proxies and may be related to client requests that trigger error exceptions on the server._

<br>

**1-What is status code 202?** Its purpose is to allow a server to accept a request for some other process.

**2-What is status code 308?** code indicates that the target resource has been assigned a new permanent URI and any future references to this resource.

<br>

**3-What code would you use if an update didn’t return data to a client?**  204.

<br>

**4-What code would you use if a resource used to exist but no longer does?** 410.

<br>

**-What is the ‘Forbidden’ status code?** 403.

---

**1-Why do we need to pull our MongoDB database string out of our server and put it into our .env?** to not be published in code.

<br>

**2-What is middleware?** Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system

<br>

**3-What does app.use(express.json()) do?** it's for inbuilt in express to recognize the incoming Request Object as a JSON Object

<br>

**4-What does the /:id mean in a route?** params object to start from the specific location.

<br>

**5-What is the difference beween PUT and PATCH?** PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource/PATCH method supplies a set of instructions to modify the resource

<br>

**6-How do you make a defalut value in a schema?** Make mongoose string schema type default value as blank and make the field optional.

<br>

**7-What does a 500 error status code mean?** Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.

<br>

**8-What is the difference between a status 200 and a status 201?** 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created.


___

<br>

_**In the end, I hope you enjoying reading, best wishes.**_

_**References:**_

<https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/>

<https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw>
