# YelpCamp
a website that enables the user to post pictures of various campgrounds, add comments and ratings.

# Requirements to test/user this project
1. A cloudinary account
2. Mapbox account
3. MongoDb

# How to setup
1. Download the zip/clone.
2. Extract it and open it in your code editor(preferrably VSCode).

# Setting up .env file
1. Make a new file in the root folder of your project and name is as .env.
2. You need to initialise some key value pairs in it you'll get them from your cloudinary account dashboard and mapbox account dashboard, and those are : CLOUDINARY_CLOUD_NAME = 'your cloudinary cloud name',CLOUDINARY_KEY = 'key',CLOUDINARY_SECRET='secret',MAPBOX_TOKEN = 'default token',DB_URL='your active mongo database url',SECRET='secret for session config'

# Starting the project server
1. Run npm install
2. Before running npm start, we need to seed our database for some random data(only if required)
3. In app.js under helmet.contentSecurityPolicy add your cloudinary account as 'https://res.cloudinary.com/<your account name/id>
4. run npm start and create an account on the server, Now you can access your USER ID in the database to use the seeds(not necessary).

# Enjoy
1. You can start posting campgrounds and post reviews accordingly.
