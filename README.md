This is a simple web app using node.js loopback server and mongodb
What this web-app do:
Store and retrive JSON data in a mongoDB collection using RESTAPIs of loopback app server.
Used ajax for data operations and update page with jQuery.
Let see how to set this app.
1.install node.js which can be downloaded from  http://nodejs.org/
2.open node.js command promt. 
3.install loopback tools by this command: npm install -g strong-cli 
Download Mongodb from here http://www.mongodb.org/downloads and download your release as per your requirement. 
Copy and extract this application some where in your pc.
now open system commond prompt
create a directory in application folder with name 'myappdb'
go to path where mongodb is installed like for me it is:
C:\Program Files\MongoDB 2.6 Standard\bin
so in cmd prompt type below commands 
1.cd C:\Program Files\MongoDB 2.6 Standard\bin
2.mongod --dbpath [path to 'myappdb' folder in web-app eg. C:\Users\SAURABH\Desktop\myworkspace\loopbackserver\myappdb 
open a new command prompt and type below commands
1.cd C:\Program Files\MongoDB 2.6 Standard\bin
2.mongo
Now the db is up and running.
Now move to node.js command prompt and type below cmds:
1.cd C:\Users\SAURABH\Desktop\myworkspace\loopbackserver
2.npm install (install dependencies)
2.slc run
application is running now which you can access from localhost:3000 in your browser
insert the new user details and you can see the json after it is submitted successfully with object id.
now press back on browser and you can see the added user is displayed on the page.
