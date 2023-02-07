# Unity-Extinguish-Fire
Putting out fire (particle systems) in Unity (2019.3.9)

Ideally, one would put the Extinguisher script onto the camera that they're going to use in the scene. 
The extinguisher is a simple script that fires a ray STRAIGHT out (there is no arc as there would be with real water) and checks if it's hitting a fire.
So, one would navigate the scene and fight fires with the camera.

The Fire script should go on an object that holds a particle system that generates the fire. In the tutorials I created (https://youtube.com/watch?v=fDUw0CjMCR8&si=EnSIkaIECMiOmarE), the fire particle systems were from Unity's 
free particle pack that also includes smoke, water, and steam (https://assetstore.unity.com/packages/essentials/tutorial-projects/unity-particle-pack-127325).

The object that acts as a fire MUST have a collider otherwise the raycasting from the Extinguisher script will not work. 
