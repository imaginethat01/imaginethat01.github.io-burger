# imaginethat01.github.io-burger

<h1>This is a simple app (Pulp Fiction Burger) - using Node.JS, MySQL, express, and handlebars.js</h1>

Our Express host address (when downloaded) is localhost:8080
SQL is hosted via localhost:3333

- We run the script Server.JS to start our application. 

<img src="projectphotos/shot1.png">

- Next! we open a web browser and enter our host address (localhost:8080)

<img src="projectphotos/localhost.png">

At this point the application hosted through Express and viewed through handlebars.js will display on our screen. 

<img src="projectphotos/fullview.png">

At the same moment that the connection is made, we can see that the app has also fetched our data from our SQL server. That data is now displayed in the console.

<img src="projectphotos/shot2.png">

Our SQL server is actually what is providing the data that is populating much of the screen. Each Burger, and its status is checked against our data there.

<img src="projectphotos/sqlconnect.png">

<h2>Let's try playing with the app some more to see what we can do!</h2>

We can create a burger entry by using the form at the bottom of the window. This data does not only exist on our current display of the application, the data is persistant. Each entry will be forwarded to our SQL server as an update. 

- let's add some burgers. 

- If we create a burger by giving it a name and a status, It will be displayed under its respective owner. Lets give jules a burger. 

<img src="projectphotos/julesselect.png">

The table is now updated!

<img src="projectphotos/julesburgers.png">

- Lets give a burger to vincent!

<img src="projectphotos/vincentselect.png">

The table is now updated!

<img src="projectphotos/vincentburgers.png">

This is what our page should now look like : 

<img src="projectphotos/allburgers.png">

 - That's a lot of burgers! - Let's get rid of the first two burgers for each character. We can do this by pressing the "Toss it!" button.

 <img src="projectphotos/burgerstossed.png">


The functionality does not stop here! - There is a lot of useful things we can do with this app... burgers are fun! - If we want to, we can switch the owner of a burger, by hitting the "Switch to partner" button

- Lets switch the burger we created for jules and give it to vincent!

We should see the changes immediately! 

<img src="projectphotos/switchburgers.png">

<h2>Don't be fooled!</h2>

This app is somewhat complicated! - There are many pages of javascript. packages, and imports / exports that are needed to make it all work right. 

Below is an example of the structure : 

<img src="projectphotos/filetree.png">

Perhaps the most important peice of insight I gained from putting all of this together is that when dealing with larger projects, being able to compartmentalize mentally, and having the patience to go over one page at a time is a valuable asset to have. 

I think it is easy to feel overwhelmed when so much is at play, but there is always code out there through NPM. GitHub, StackOverflow and other sites that are worth referencing. If a code functions and is written in best practice, why mess with it too much? 

When I am dealing with packages or API's I find getting back to the basics and really looking over the published docs that are put out by the publisher to be a helpful resource. 

The code for Express below is almost exactly what is refenced in the docs :

<img src="projectphotos/expressconnect.png">

- A lot of publishers know that dealing with API's and huge amounts of packages can get really complicated, so a lot of the code they actually host on their webdocs or elsewhere is often written as simply as possible! - It is amazing what you can get out of a NPM Readme! 











