# Android-Study-Jams

College Bus Tracking System
Problem Statement:

Over a great period, many issues have been faced by our students traveling by college busses. One of the challenges they face every day is to know the location of the bus.
Technology plays a vital role in day-to-day life activities which in turn made great changes in many work fields and out of them Mobile Application is one of the major developments. Mobile Application can be used effectively for this job as they are widely used and are known for easy access.
Proposed Solution :
This project proposes a “Bus Tracking System” to keep track of the college bus and provides all the information about GNITS Bus Services. Its features include location of busses and prediction of bus delays. It accepts student data allowing them to register to the application. This application uses GPS tracking techniques by acquiring the geo-location from the driver's mobile device and mapping it to the database. Google API’s are used for accuracy in finding the location of the busses. Currently the app works for GNITS institute only. The project's scope is to extend it for other institutions to transport services in future in collaboration.

<img width="559" alt="sampleimages" src="https://user-images.githubusercontent.com/18289261/142846646-a6858641-ad88-43aa-b8bb-b690fd7126f1.png">
    	  	
Functionality & Concepts used :

The App has a very simple and interactive interface which helps the students select their route bus and track its location. Following are few android concepts used to achieve the functionalities in app : 
Constraint Layout : Most of the activities in the app uses a flexible constraint layout, which is easy to handle for different screen sizes.
Simple & Easy Views Design : Use of familiar audience EditText with hints and interactive buttons made it easier for students to register or sign in without providing any detailed instructions pages. Apps also uses App Navigation to switch between different screens.
RecyclerView : To present the list of different route busses we used the efficient recyclerview.
Google Maps API : We are also using the Google Maps API free version for  below 1000 users. In future if the user base increases we will go for the upgraded plan too.
LiveData & Room Database : We are also using LiveData to update & observe any changes in the Bus driver's locations received from their mobile at real time and update it to local databases using Room. Coordinates are then updated in the bus route screen and students can track their route bus locations.

Application Link & Future Scope :

The app is currently in the Alpha testing phase with GNITS institute with a limited no. of users, You can access the app : [YOUR APP LINK HERE](either Github link or Google Play store link of published app or .apk file).

Once the app is fully tested and functional in GNITS institute, we plan to talk to neighboring colleges also to propose this app idea and collaborate with them on this transportation service. We aim that by next year most of the colleges in our district will use Bus tracking apps to check out their bus routes and be informed all the time. Also we are planning to include emergency SOS features for students traveling in busses if they are stuck somewhere. 
