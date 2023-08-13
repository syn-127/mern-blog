# Mern Blog

This application was created using the mern stack (mongo db, expressJS, react, nodeJS). This was mainly created to have a blog on my portforlio website. Though would be nice to build and have my own features that I want. 

## To run Locally

At the moment I haven't dockerized the application yet but will in the near future. So if you wish to run this locally you have to do 2 things.

You need to open 2 terminals.

In one terminal do the following

```cd api```

then

```npm install```

this will install the depandancies. Once this is done you will need to add your own MongoDB url to your database to the .env file. You can either create a .env by simple making a text document and adding the varibles and values like so:

```MONGODB="string"```

You will also need to add one for bycrpt but this can be any random characters and can be anything you like. This is used to generate the salt hash it can be any character length but I suggest the longer the better:

```BYCRYPT_SECRET='ABC123456789'```

Once you have done this you are ready to run the server , to do this run the following on the terminal:

```node index.js```

this will start the server. The server will use port 4000.

Once that is done on the other terminal you need to change the directory to the client folder.

```cd client```

once here you need to do the same as before and install the dependancies

```npm install```

once done run the command

```npm start```

this will start the front-end and will run on port 3000. Once both are up and running you can begin to use the application.

