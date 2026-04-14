Log infos:
- Start time
- Duration
- Weather:
    * Fair
    * Rain
    * Snow
    * Hail
    * Sleet
    * Freezing Rain
    * Fog
    * Other
- Road Type
    * Highway
    * Major Road
    * Local Road
    * Rural Road
    * Urban Road
    * Parking Lot
- Time of Day
    * Day
    * Night
- Notes Textarea


# Devlog 6

Kind of a mixed day today. First 45-60 minutes of this devlog were spent fixing issues regarding the uploading migration feature, which had some mismatches and utilized the unused miles feature. You can see in the video now that the total time added up is now correct, as in the previous devlog it just concatenated all of the strings together as one. Also fixed some parsing issues with the road type and standardized the data so its easier for me to work with later.

For the rest of the period, I decided to get started with React Native! After a short tutorial and testing out for a bit I've started to work on the basic design and test it on an IOS simulator. The learning curve is a little strange since everything is familiar but also so different in execution, but I kind of replicated the login page that I wanted? I began to implement the firebase dataset inside this and I'm planning on fully implementing that later!