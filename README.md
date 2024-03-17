# COMP3015
 COMP3015 30PCNT

 This project was created in Windows 10 (Version	10.0.19045 Build 19045) using the software Visual Studio 2022 (Version 17.9.3).
 The code is broken into different files. 
 The .frag and .vert files act as the shaders. Frag is broken down into declaring the values of mainly diffuse, specular and ambient values of the different light sources and materials, which are then used in the phong lighting shaders. The spot and Ambient phong shaders are then used to calculate the colour of the scene in the main() function. 
 The scenebasic_uniform.cpp and scenebasic_unform.h are where the initialisation and rendering is done. the header file is used to initialise all the models and assets used in the .cpp file
 the .cpp file compiles initialises and animates the assets so that in render they can make use of the phong shader by inserting set diffuse, specular and ambient values to create a convincing scene. 
 Main.cpp runs the scene so that it can be visualised. 

 In terms of construction. I've used toruses of different sizes to create the lava pool then a multilight system to create the emerging lava and finally a rotating spotlight to simulate moving lava. As well as the sin() wave on the Y translation of the skeleton model to simulate bobbing up and down
