# BE-TEST
Back End Test for Kitalulus

To be perfectly honest, I am still a novice to nodejs but I do have experience working with vanilla JS and Angular so the tutorials were easy to understand

During development, I used npm run dev to automatically serve my changes. To facilitate requests, I used postman and ran my requests there. Of all the requirements presented, I was not able to dockerize my app as I was running out of time and I cannot understand how to make it work

As for my questions regarding requirement 5, I just made it so that the request will show all the details of a specific requested question instead of all of them
With the delete requirement, I did not delete the requested question, instead, I change the "IsActive" status to false as it is bad practice to delete records in the database. Speaking of which, I utilized arrays and hardcoded the data used during my testing

In order to run the code in dev mode, just type npm run dev and nodemon will be the one to facilitate the updating and use Postman for the requests.

I zipped the node modules folder to upload it here as I was having a hard time with github for some reason, just extract the folder or reinstall the dependencies.

The logger middleware is commented out within the app.js

Thanks!
