# 2D Platformer
This is a personal project to become familiar with the Unity platform and tools. So far, dynamic player sprites have been added along with background sprites and tile maps for quickly developing basic 2D maps. The game uses ray casting for movement and collision detecting instead of the built-in Unity 2D physics system because this leads to more responsive game mechanisms. A ray casting controller has been added. Player, platform and other moving objects inherit from this controller and therefore use ray casting for movement & collision detection. The relevant scripts for this can be found in the [2d-platformer/Assets/Scripts](https://github.com/Aviral-Salhotra/platformer/tree/main/2d-platformer/Assets/Scripts) folder and the ray casting  based off of [Sebastian Lague's tutorial series](https://youtu.be/MbWK8bCAU2w) for 2D game design.

The following demo shows the ray casting in action. The red lines demonstrate the rays projecting from the character sprite and their length is proportional to character velocity. These rays are used to detect collisions with ground and other objects.    

![Ray Tracing Demo](https://user-images.githubusercontent.com/24803574/135701880-f7381e67-52fb-44ca-8b05-d0fb0221cd1e.gif)

# Progress
- [x] Player Controller: use ray tracing and add movement and jump actions movement
- [x] Create tile pallete for level design
- [x] Create basic level for prototyping 
- [x] Add moving platforms
- [ ] Add collectibles and inventory
- [ ] Add three enemies with varying difficulty levels and implement their controller 
- [ ] Add camera controller
- [ ] Player Controller: add combat sprites & mechanism for weak attack and strong attack. 
- [ ] Player Controller: add ranged weapon and targeting and shooting systems
- [ ] Add Score System and Level Completion Animation
- [ ] Add two additional levels
