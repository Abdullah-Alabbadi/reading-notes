# Read: Class (11) Authentication

## There is some important question we should ask us about Authentication:

---
<br>

**What is OAuth?** It allows websites and services to share assets among users. It is widely accepted.

**Give an example of what using OAuth would look like** When you want to Sign Up onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.

**How does OAuth work?** What are the steps that it takes to authenticate the user?

**#1how is work:** Let’s assume a user has already signed into one website or service (OAuth only works using HTTPS).


**#2steps of work:**

**"The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.**

1-The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

2-The first site gives this token and secret to the initiating user’s client software.

3-The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

4-If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

5-The user approves (or their software silently approves) a particular transaction type at the first website.

6-The user is given an approved access token (notice it’s no longer a request token).

7-The user gives the approved access token to the first website.

8-The first website gives the access token to the second website as proof of authentication on behalf of the user.

9-The second website lets the first website access its site on behalf of the user.

10-The user sees a successfully completed transaction occurring.

11-OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems.

*What is OpenID? It's is about authentication: as a commenter on StackOverflow and for humans logging into machines, serves as a single sign-in.

----

*What is the difference between authorization and authentication?**

**#Authentication** is the act of validating that users are who they claim to be.

**#Authorization** in system security is the process of giving the user permission to access a specific resource or function.

**What is Authorization Code Flow? exchanges an Authorization Code and replace it with a token.**

**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?** It's additional security. Additionally, single-page apps have special challenges.

**What is Implicit Flow with Form Post?** it's as an alternative to the Authorization Code Flow, provides the Implicit Flow, which is intended for Public Clients, or applications that are unable to securely store Client Secrets. 

**What is Client Credentials Flow?** its system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username password or social logins don't make sense.

**What is Device Authorization Flow?** it's device Authorization Flow
With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. 

**What is Resource Owner Password Flow?** highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.

<br>

_**In the end, I hope you enjoying reading, best wishes.**_

_**References:**_


<https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html>

<https://auth0.com/docs/flows>