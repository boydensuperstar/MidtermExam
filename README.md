# Midterm Exam

Complete the following inside the Unity Project contained within this repo. 

1. Use the GitHub repo assignment link.
2. Create a terrain with a minimum of two hills. (No Gaia for those who have it)
3. Create a tree with a minimum two branches and two leaves.
4. Add a windzone that blows the leaves of the tree. 
5. Make the terrain, tree, and wind zone children of an empty GameObject called Environment.
6. Create a 2 meter tall wall around the terrain that is child to an empty called Wall.  You will add a culling mask to the wall so that the camera cannot see it.
7. Create an empty GameObject called House and create a house-like structure that contains a door-like opening on one side and a small opening in the roof.  The house-like structure objects should be children to House GameObject.
8. Create an empty GameObject called Decor and child a FBX or OBJ found off a 3D model site.  The 3D model should be placed inside of the house. 
9. Under the Decor game object, create three primitive capsules, two primitive spheres, and two primitive cubes. These objects should all be inside of the house-like structure.
10. Add an emissive green material to one of the spheres. 
11. Make the other spehere a fade object with a material of your choice that is not used on any other objects (other than the default material). It should be at a 30 - 50% fade. 
12. Add a non-specular, non-emissive red material to one of the cubes.  Smoothness should be less than .5.
13. Make the other cube a glass-like transparent object with a material of your choice (other than the default). The material should not be used on any other object in the scene. 
14. Add a standard specular shader to one of the capsules, making the albedo color be a complementary color to the specular reflection. Meaning the capsule should be blue and the specular should be yellow/orange (or any other complementary color set). 
15. Download a free texture from https://3dtexture.me that has a texture, normal map, height map, and occlusion map.  Create a material using these textures and add it to one of the capsules (the one without the specular). 
16. Make the remaining capsule a reflective material that will reflect a reflection inside of a reflection probe.  
17. Add light probes in the entire house area.
18. Add a dim point light in the house.  The range should reach the ceiling, floor, and two walls that meet in a corner. 
19. Add one reflection probe and be sure that the reflective capsule is inside the reflection probe and reflecting the interior of the house. 
20. Add the first-person character from the Standard Assets Pack and place the character near the outside of the house. Disable the MainCamera at the top of the hierarchy (the one always in a scene). The FPSContoller has a main camera on the child object for the Main.
21. Outside of the house, build a snowperson with primitive objects and turn the snowman into a prefab.  Place the prefab in a folder in the project area entitled, "Prefabs". 
22. Light the snowman with a colored spot light that is intense.  
23. Change the skybox to a different skybox than the default (you'll need to find one). 
24. Add a tracker module to the snowman from https://modarchive.org/
25. Add a hemisphere shaped particle system to the snowman that changes colors over the lifetime of the particle. You will also need to change the material of the particle to Default-Particle. 
26. Add grain post processing to the camera and make sure the grain is noticeable.  FYI, the MainCamera is on the FPSController's child called FirstPersonCharacter. 
27. Make sure the wall that you created earlier around the terrain is not visible with the culling mask. 
28. Be sure the project window is properly organized with the assets in organized folders that are easy to understand. 
29. Add the scene to your build scene. 
30. Commit to GitHub. 
