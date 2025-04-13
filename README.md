
![Screenshot of the projectt](/Screenshot/BannerCrop.png)</BR>

# FlyingPathfinder (PublicDisplay)
This project aims to create a pathfinding system for characters that can both fly and walk in Unreal Engine 5

## Disclaimer
<b> This page is only a public display to showcase updates of the tool while it is still in development, until its release on Fab.com. The actual source code is hosted in a private repository on this GitHub, but if you want to have a look at it for any valid reason, feel free to contact me at gforget2@gmail.com </b>

## Update Video :
Initial Presentation:</br>
<i>Coming soon </i>

## Feature included in the prototype
- Custom volume box that automatically generates the 3D grid for air navigation
- Works in tandem with the navmesh system for walking locomotion
- Uses the flying property value in the Movement Component to control character movement (although it needs some calibration in the FlyingMovementComponent to work well)
- FlyingMovementComponent to help calibrate flying movement and define whether the character should fly, walk, or be controlled by another condition
- Optimized path generation using A*, with a grid partition system to quickly retrieve points in the grid based on a 3D position

## Demo scene include
- A mage-like character with integrated animations that can both fly and walk
- A custom controller that allows selection of 3D space points in the air and on the ground

## Current limitation (which will be adress in the future)
- Character can only move within the boundaries of the FlyingPathfinderVolume
- One movement request cannot currently combine both walking and flying. However, if movement is set to handle both, it will pick the shortest path used by either.
- Animation blending for the mage could use some improvement (although pretty good for a prototype)



