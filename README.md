# Childhood

### Tools Used: Meshy AI, Blender, A-Frame, React, JavaScript, HTML, CSS, Netlify

### 🚀 Deployment childhood-pinwheel.netlify.app

### 1.	Description
This project explores how to use AI to generate 3D assets and combine them with traditional tools such as Blender to create interactive XR experiences. The scene includes a stylized Sichuan snack street, animated lanterns, panda models, house models… As well as interactive elements made with A-Frame.
 
### 2.	Pipeline Overview
 🧠   3D Asset Generation
Meshy AI was used to generate stylized 3D models based on image inputs (e.g. pandas).

 🛠️   Blender Editing
All generated assets were imported into Blender for cleanup, mesh optimization, UV mapping, and material adjustment.

🌐 A-Frame for scene assembly and interaction
This immersive XR scene is built using A-Frame, leveraging its capabilities for animation, interactivity, ambient sound, and clickable elements. 
The user can interact with various parts of the scene for informative and visual feedback:
-	Food Truck: Clicking on the food truck triggers a popup introducing my hometown—Chengdu, with details about its food and culture.
-	Panda Picture: Clicking on the panda image on the right opens an introduction to pandas, including fun facts and their symbolism in Sichuan.
-	Ancient Chinese Building: Clicking the traditional house in the distance makes the building glow more brightly, highlighting its significance and drawing attention.
-	Play Music Button: Clicking the “Play Music” button in the upper-left corner begins playing the Chinese classical background music. Click it again to turn off the music. Note that you need to double-click the button the first time you click it.

🌐 Interactive Game with JavaScript
A mini-game is integrated into the XR scene using JavaScript. Here's how it works:
-	Start Game: Clicking the "Start Game" button in the upper-left corner begins a countdown timer displayed in the top-right panel.
-	Gameplay:
     -	Users can click on lanterns, tables, windmills, and other interactive objects to gain points.
     -	Most objects, once clicked, will disappear and add 10 points to the score.
     -	The large central lantern is a special object—it adds 1 point per click but does not disappear.
-	Challenge: Two moving lanterns are included to increase the difficulty, requiring better timing and attention from the player. And not every objects can be clickable, you need more patience to find objects to click on to get higher scores within a limited time.
-	End Game: When the 30-second countdown ends, you will get your final score at the top center of the scene.


### How to run the project

1. npm i
2. npm install aframe
3. npm run dev
