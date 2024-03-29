# musicapp
PROJECT SPECIFICATION

➣ The app’s structure is suitable for a music player app. A similarly structured app which focuses on audiobooks, podcasts, or other       audio media is also acceptable.

➣ The purpose of each activity is easy for a user to understand through the UI design and feature labeling.

➣ The app contains 2 to 6 acti vities.

➣ The app contains multiple activities, each labelled, which together make a cohesive music app.

➣ Features in the app are clearly defined either by labelling or images. For example, a button to play music could use a universally       recognized triangular "Play" symbol or could have the text label "Play".

➣ Each activity contains button(s) which link it to other activities a user should be able to reach from that activity. For instance, a ‘ Library’ activity might contain a button to move to the ‘Now Playing’ activity.

➣ The code adheres to all of the following best practices:

o Text sizes are defined in sp<br>
o Lengths are defined in dp<br>
o Padding and margin is used appropriately, such that the views are not crammed up against each other.<br>
o Each button’s behavior is determined by an OnClickListener in the Java code rather than by the android:onClick attribute in the XML         Layout.<br>
➣ Each button properly opens the intended activity using an explicit Intent.

➣ App uses a custom adapter to populate the layout with views based on instances of the custom class.

➣ Information about instances of the custom class are stored in an appropriate data structure (e.g. ArrayList, Array). When the           information needs to be displayed, it is efficiently retrieved (e.g. Looping).

➣ Data about each song (or equivalent audio media such as podcast episode) should be stored in a custom class that contains at least 2     states (e.g. Song Name, Artist Name) If images are included (e.g. Album Art), they are stored as drawables. All drawables are stored     at multiple densities. Images are not required.

➣ About Musical App

➣ The app contains 3 activities.

   o MainActivity<br>
   o SongsInAlbumActivity<br>
   o NowPlayingActivity
➣ This app only shows the structure of the app and how the app transit from one Activity to another Activity. (eg: From MainActivity to   NowPlayingActivity etc...)
