Indian Election Results - 2014
==============================

An experiment to check out how realtime apps can be built with [Firebase](https://www.firebase.com/).

#####You can view the site here - https://dazzling-fire-5510.firebaseapp.com/

### About the elections
The 2014 Indian elections are the largest democratic elections to be carried out anywhere over the world. The elctions had 9 phases of voting spanning 40 days. The results for the same will be counted on the 16th of May 2014. I'll be updating results as they would be coming in using the realtime update api.

For the unitiated, the elections are a multi-party affair. The two main parties are the INC (Indian National Congress), that has been running the government for the past decade as part of the UPA (United Progressive Alliance) coalition, and the BJP (Bhartiya Janata Party) that is running as a coalition called the NDA (National Democratic Alliance). However beyond these two major coalitions there are atleast 12 other major regional parties that can hold the key to the results by aligning with one of the two or forming a third front. There are plenty of places on the internet to learn more about the elections. You can start with [Wikipedia](http://en.wikipedia.org/wiki/Indian_general_election,_2014).

### About Firebase

Firebase is a data store that lets you build realtime apps. That means that you write your app (web or mobile) and use the firebase apis to store and retrive data. If your app is open, it updates the data automatically without you needing to refresh the page. That is what is called as realtime. The folks at Firebase do an excellent job of [onboarding a user](https://www.firebase.com/how-it-works.html). 


There is a [REST API](https://www.firebase.com/docs/rest-api.html) available to create, update, read and delete data. Your code can [listen to changes](https://www.firebase.com/docs/reading-data.html) via callbacks. Moreover you can [host the project](https://www.firebase.com/docs/hosting.html) including the static content with Firebase.


##How the code is organized

* All the HTML and JS is in `index.html`.
* Libraries are included via whatever available CDN using HTTPS since Firebase prefers HTTPS.
* Libraries included are `firebase` and `jquery`.
* All the css is in `assets/css/project.css`. The Google Now style card interface is borrowed from [here](https://gist.github.com/eLindemann/5287591).
* The REST APIs used to update the data are available as a [POSTMAN collection here](https://www.getpostman.com/collections/413030f038460d0121ff). If you don't use [POSTMAN](https://www.getpostman.com/) for your API development, you should now!
* The web app has been deployed to Firebase here - https://dazzling-fire-5510.firebaseapp.com/.
