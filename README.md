This project links an iOS app with a Node.js http server and a Mongo database. The iOS app tracks a specified iBeacon region and reports to the server upon entering and exiting the region. The server stores this data in MongoDB. The information can be viewed in both log and table form at helloworld-20553.onmodulus.net. The username and password for the database are stored in a config.json file which has not been uploaded. Anyone wishing to use this source code would need to create their own local config.json file with credentials specific to their database. 
Furthmore, each user in the database is tied to a Phillips Hue light, so when they enter or exit the building their corresponding light will flash.
Finally, the lights can be independently controlled through an iOS app.