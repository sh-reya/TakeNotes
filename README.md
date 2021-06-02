# Full Stack Android App
## TakeNotes [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fsh-reya%2FBuzzFeed&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

#### About
   This is a full-stack application that is quite similar to the notes taking app of our android sets.
   
#### Tools and Languages Required
<list>
  <ul>
    <li>Android Studio</li>
    <li>Kotlin</li>
    <li>xml</li>
    <li>recycler view</li>
    <li>Layout manager</li>
    <li>Android architecture</li>
    <li>Room Database</li>
    <li>DAO</li>
    <li>Repository</li>
    <li>View Model</li>
    <li>UI</li>
  </ul>
  </list>
<h4 align="center"> The Plan to carry out this project is as follows:</h4>

<img src="img/n1.jpg" align="left" height="650" width="550"> 

It works on Android Architecture Components. The app uses a real time database in the backend where a user can write and save their notes. On refreshing the app, all their data remain intact. If the user decides to delete a particular note, then that data is removed from the database.

### RoomDatabase
   Room is basically a wrapper over sqlite. We access the data of Room using DAO    i.e., Data Access Object.

### Repository
   A single source of truth for data, that handles data coming from multiple places.

### View Mode
   View model seperates data from activity. This is known as seperation of concern.
   It is made LIVECYCLE AWARE, i.e., change of data is appeared in real time.
   It does not destroy, data and recreates new data while we rotate our phone from    portrait to landscape mode.
   It survives the configuration change.

### UI Controller
  This is the part of the application that gets displyed.
   
   
<br><br><br>
<h3 align="center">Output Images:</h3>
<br>
<p align="center"><img src="img/2.jpeg"  height="600" width="350"> <img src="img/3.jpeg" height="600" width="350"></p>
<br><br>
<p align="center"><img src="img/1.jpeg"  height="600" width="350"> <img src="img/4.jpeg" height="600" width="350"> </p>
