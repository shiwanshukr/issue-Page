# issue-Page
Connecting nodeJs server

Deployed an issue page through nodeJs, jayde, css, and react.

Pre-Req:
1. nodeJs installed
2. npm installed
3. Express Framework. (nodeJs with express)
4. I have used Git bash (optional) -- You can simple use command line
    In Git-bash use ^c to come out of it and restart the server.
5. IDE: Visual Studio Code or anyone
6. Response code - 200 working fine & 400 not working fine
7. Finally make sure that you have allowed access through non secured apps for any SMTP mail.



Several node modules are also installed when you create the dependencies. 
Express (nodeJs module) - 

It gives us a full framework, it gives us a routing system in the server. To install it, we do npm install express. 
Although we will use gFlag because we want to use globally so we could access it from anywhere.
we will be using nodeMialer to redirect the smtp emails.
Jayde - works really well with express.

Body-Parser is an important concept:
Body-Parser streamlines your data components across internet. 
Use bodyParser() if you want the form data to be available in req.body.
application/x-www-form-urlencoded
multipart/form-data
application/json
application/xml
As we have various formats of data like Json, xml, & etc we use bodyParser to streamline the data.
