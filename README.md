# Gec-Talks
This is a chatting app which implements AWS and parse server
So Let's Get Into Its Details That How It Workss....

In order to create a chat application, you should be aware of any programming language and an Integrated Development Environment for
app development and should have a database server to store/fetch all the inputs sent by users when required. There are many companies 
that offer their servers like MySQL, PostgreSQL, Microsoft Access, SQL Server, FileMaker, Oracle, RDBMS, dBASE, Clipper, FoxPro and Parse.
I used Parse Server i.e., an open-source Backend-as-a-Service(BaaS) framework initially developed by Facebook for my own application. 
To get to know more about pasrse go https://parseplatform.org That's it you are good to code.

In my application, I have used Parse Server as the database server, Android Studio as the IDE (Integrated Development Environment) and
JAVA to program.
Here are some of the sample algorithm you would need
1: To create Class, tuples and feed the data on the server
Here in this program, our Class is Score which is more like a table_name; username, score are the tuples on the table name Score which have values rob, 86 respectively.
2: To get data from the server to your local system

Here SFQaU4UXfv is the object id made automatically by the server (each and every attribute which is uploaded to the server have their 
own object id) which is used to get the data stored at this id.
3: To check whether any user is logged in or not, if logged in then get the username

getCurrentUser is a well-defined function of parse that gets the credentials of the current user who is signed in.
4: To verify username and password given by user from the server

logInBackground function compares the data with the data provided by the user.
5: To make new user signup with a unique username

There are a lot more modules to create a chatting app if want to learn all, go to my project link mentioned below.
VikasPandey121/Gec-Talks
