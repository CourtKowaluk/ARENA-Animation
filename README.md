# ARENA Animation
This details the process of creating a simple animated 3D model in Blender, and then animating it on a click event in the CONIX ARENA. It uses MQTT as a primary way of initalizing and communicating with the ARENA.

## Getting Started With Modeling
For this, Blender is used, as it is free and versatile. However, any other 3D modeling & animation software will suffice, as long as the file is exported to a *.glb or *.gltf format. 

[Blender can be downloaded here.](https://www.blender.org/download/)

Install Blender according to the instructions for your OS. I'm using Blender 2.80 for Ubuntu 18.04.4.

## Starting Blender
When you start Blender, choose to open a General new file. ![tutorial_01](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_01.png)

Your screen should open to the Layout tab, with a grey cube in the center of the scene. You'll have a camera, cube, and light in the top right Scene Collection window. ![tutorial_02](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_02.png)

### Creating New Models
For this tutorial, we will be using two shapes. In this case, I will be using a cube and a sphere. At the top of the screen to the left, click Add > Mesh > UV Sphere. ![tutorial_05](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_05.png) This will add a sphere to the origin of the scene. 
![tutorial_06](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_06.png) 

Use the Move tool to move the sphere from the center. Move the sphere to the starting position of your choice. 

### Changing colors
In the bottom right Context menu, you can select many different tabs. To change the color of the rendered object, you can edit the Base Color and Subsurface Color in the Material tab. ![tutorial_03](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_03.png) This will not show up in your Blender window, however it will be in the complete render when it's exported. To change how it appears in the scene, scroll down to Viewport Display in the Material tab. ![tutorial_04](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_04.png)

To change the color of a sphere or new mesh created, there are a few additional steps. If you select the sphere in the Scene Collection menu and go to the Material tab of the Context menu, you will notice there are no presets or settings to change, unlike the already-generated cube. Create a new material, name it whatever you want, and you can change the colors, materials, and display. 
![tutorial_07](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_07.png) ![tutorial_08](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_08.png)

### Starting Animation
At the top of the window, change from the Layout tab to the Animation tab. This window will look different, with a preview on the left, scene in the middle, and a timeline at the bottom. Right click on the cube, select 'Insert Keyframe', and select 'Location'. ![tutorial_09](https://raw.githubusercontent.com/CourtKowaluk/ARENA-Animation/master/images/tutorial_09.png) In Blender, a keyframe is a specific frame in the timeline that contains the attributes of models, such as their location, rotation, or size. You can read more about Blender keyframes [here.](https://docs.blender.org/manual/en/latest/animation/keyframes/introduction.html)
