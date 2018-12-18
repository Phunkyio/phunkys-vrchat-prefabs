# phunkys-vrchat-prefabs
World/avatar prefabs for Unity 2017 created for VRChat

## Animations
### laying-idle.anim

## Prefabs
### phunky-stream-panel
Based off of jetdog's stream panel prefab. Screen was rebuilt to use a separate game object, so that multiple screens can use the same video without having to load it more than once, triggers were changeed to allow the input of multiple video sources into a playlist, and a trigger was added to disable master controls to allow everyone in the room to control the video and input links. There is a bug with the resync trigger function, which is specific to the VRChat SDK. If you want the screen emissions to be a part of global illumination, you have to turn off the screen-reflect object before baking lights.