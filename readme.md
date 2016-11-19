# 3D Scene rendering for a video game

## Description

In this project, I load a scene using [Assimp](http://www.assimp.org/). I also add characters (deers) and a personal model I created, using [Blender](https://www.blender.org/).
Then, I render the entire scene with the [Phong reflection model](https://en.wikipedia.org/wiki/Phong_reflection_model).
I also added camera controls : you can move in the scene using the laters QZSD (like arrows on an AZERTY keyboard).

## Compile the project

To compile this project, you should update the properties before.
It is necessary to update the dependencies (glew, freeglut, glm and assimp).
- Right click on the project name in the solution explorer
- Go in C/C++ -> General -> Additional Include Directories 
- Change the full path for the directories (they are in the GitHub project so you can find them easily)
- Do the same for Linker -> General -> Additional Library Directories 
- Do the same for Linker -> Input ->  Additional Dependencies 
Then you can begin to use this project !

## Load the models

The model files are present in the assets directory. You can either copy them in your working directory (Debug or Release) or add the full path in main.cpp file.
They should be loaded correctly once you have done that step.
