# React native ondrive sdk

OnDrive is an SDK which allows location tracking.

# SDK Installation
npm install ondrive --save

>An API Key Must Required.

```
import OnDrive from 'ondrive'
objLocationUpdate.DebuggerMode = true; //Default False.
objLocationUpdate.APIKey = ''; //Must Required.
objLocationUpdate.contactInfo = '';
objLocationUpdate.updateAfterInSeconds = 5 //Default 3 Seconds.
//On action start.
objLocationUpdate.start(); // Start tracking.

//On action stop.
objLocationUpdate.stop // Stop tracking.
```

>Hurrah!!<br>
>Tracking will start automatically.

