# 3D_City_fbx

This repository contains .fbx versions of virtual Oulu models. The original ones (blend or 3ds) and workfiles in .blend -format can be found from other repositories.
Use Git large file storage (https://git-lfs.github.com/) before cloning.

When importing the models to UE or Unity, remember to also include texture -folder in the same location your .fbx file is.

In this repo each building is its own object. Each building is on its designated area (map.jpg), 
but the buildings area named based on the address they are on on the south-north streets e.g Isokatu, Kirkkokatu... 
(Streets that go west-east are not used in naming the files apart from textures). All textures required for a speific 
building can be found from subfolder /textures. Some building may contain more than ten material files, the reason 
for this repo in part is to have a version control for joining the materials and atlassing/updating the textures, to make it easier to export these models and create big scenes in Unity, UE4, Meshmoon etc.

Materials are licensed under separate Creative Commons licenses for runtime exports and model source files, more infor at: http://www.ubioulu.fi/en/VirtualOulu

Map describing the areas:

![alt tag](https://github.com/Plij/3D_citymodels/blob/master/areas_map-3.jpg)

