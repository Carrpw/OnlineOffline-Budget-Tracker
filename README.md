# OnlineOffline-Budget-Tracker

## Files Included:

* Javascript x6
* Icon x2
* html x1
* webmanifest x1
* css x1
* json x2
* .gitignore
* readme

## Description of Process

I started this project by creating a heroku for it, linking the github repo to heroku, and linking that to a mongodb. Once that was created I went into the server.js file and added the MONGODB_URI to it along with an alternate port if the local 3000 was unavailiblel. I then added the db.js file that was given by the instructor due to time constraints. Next I made a manifest.webmanifest file that had both of the icons that were given in it and added a link the the file in the index.html. The next file I made was the service-worker.js and the files I precached were all the files in the public folder. Once those were listed I made the install function, activate function, and fetch function which, is vital to caching the infortion so that if the application is offline it can pull from the cache. 

Heroku Deploy: https://tranquil-sea-22386.herokuapp.com/
Github Repo: https://github.com/Carrpw/OnlineOffline-Budget-Tracker

![Screenshot (116)](https://user-images.githubusercontent.com/73077219/103847938-4722ff80-506f-11eb-81c3-6419f6905c00.png)