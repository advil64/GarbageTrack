## Inspiration

(Scripts not pushed)

In a world in which we can clearly see the costs of centuries of environmental carelessness, much importance is placed on the individual’s promise to be environmentally responsible. However, we realized that something so fundamental to today’s environmentalism was marred by problems- that the recycling process was far from perfect, marred by inefficiencies even before recyclable materials were even picked up. We wanted to do our part to help our planet by not only encouraging recycling, but also by improving the infrastructure of the recycling process to ensure that every piece of recyclable material does as much good as possible.

## What it does
“Garbage Track” uses sensors installed on the bottom of a garbage can or dumpster lid to track precisely when these units are at maximum capacity. Sanitation workers can then utilize our app to coordinate and optimize their efforts. By only collecting recycling material from units that are full and not stopping to check units that are empty or only partially full, sanitation workers would be able to cut down on wasted gas, time, and effort.

## How I built it
This app was built using Android Studio, Firebase, a button, and a Dragonboard 410c. Using Python3, the Dragonboard and button were programmed to respond to being pressed by sending a true or false value to the Firebase that contains a database of sensors. The app, created by Android Studio, will display a map with the location of every sensor. When true, we programmed the app to display the location pin as green; however, when false, the location pin will appear red.

## Challenges I ran into
Some challenges experienced throughout the process of making this app included getting the app to connect to the Firebase database, to get the Dragonboard and button to respond to being pressed, and to add/retrieve information from the database. To solve the connection issues, we had to readjust some of Android Studio’s compiling settings. The issue with sending/retrieving data was that this was the first time we had to program this function in Python3. Lastly, the Dragonboard issue was challenging as this was our first time using the Dragonboard and we had to program it in Python3, a language that we weren’t too familiar with.

## Accomplishments that I'm proud of
Some accomplishments we achieved included learning how to connect and use the Dragonboard and touch sensor, learning to send and receive data from Firebase, and overall being able to transfer information across platforms.  

## What's next for GarbageTracks
We hope to expand our focus from recycling to garbage collection as well, which could potentially help make the entire waste collection process more efficient. In addition, we hope to be able to use ultrasonic sensors to be further accurate and descriptive of the amount of trash in a given trash container. 


