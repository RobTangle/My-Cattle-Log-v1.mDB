# My Cattle Log - Livestock App

My Cattle Log is an application that is meant to be used by farmers who want to keep a record of their cattle status.
By loging in to the application with their google, apple, linkedin, or personal email, they can update information about their animals: Date of birth, SENASA ID, Tracking device and number, if the animal is pregnant, male or female, age, images, comments, etc.
Also, My Cattle Log will automáticly produce statistics of the records uploaded, sorting and ordering the cattle in different catogories with instants access to any animal detail.
In the profile component, the user can create personal notes to register any relevant information that they wanna save in one place, accesible to them all the time.

## How to run the front-end:

From the main directory, follow this commands:
cd client/

npm install

npm start

## How to run the back-end:

Create a new database called "Cattle_Tracker_DB" with postgres or in the /api/src/config/config.js file set the appropiate configurations for your own Data Base.
After having the Database prepared to be synced, in the directory /api run the following commands:

\*If you haven't installed the packages yet, run:

npm install

npm run dev

\*If you already installed the packages with the command "npm install", now type the following command to run de back-end:

npm run dev

Now you should have the front and back-end running!

## NOTE:

By default, the front-end will run in the PORT 3000, and the back-end in PORT 3001. You can change this configurations in the file /api/src/config/config.js
