# AR-Furniture-Previewer
Made with Vuforia and Unity C#

<img src="https://lucasgigliozzi.com/wp-content/uploads/2019/11/furniturepreviewer-1-144x300.png" width="200" height="430" />

### Description:
The AR Furniture Viewer is a mobile application compatible with Android and iOS (only tested on Android) that imposes models of furniture on top of a live environment video feed.

### Languages/Libraries/Frameworks:
Unity, C#, Vuforia

### Explanation: 
The application imposes 3-D models of furniture over a video feed from a users camera. This gives it the illusion that the piece of furniture is actually there, so the user can see what it would be like if the piece of furniture were in their house, for instance. More 3-D models can be added, depending on what furniture needs to be previewed. 

### How it works: 
Unity was used for the models and environment along with Vuforia’s custom Unity objects. This allows the application to take input from the camera and use it as the environment. Additionally, Vuforia allows for plane sensing, so objects are not floating or placed randomly, but rather, instantiated on the ground. And finally, the chosen model does not move with the camera, it stays in place even if the users camera moves somewhere else. These features allow the piece of furniture to look as real as possible, despite being imposed.


