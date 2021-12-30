# 3D-Gallery

A simple project demonstrating a Blender + Unity workflow to build a 3D Gallery

### [View the gallery here!](https://nathanmargaglio.github.io/3D-Gallery/)

## Process

First, I found and downloaded a [3D model I could use in Blender](https://free3d.com/3d-model/donut-716088.html).  You could, instead, create your own 3D model (which would be more impressive), but I just imported this model, made some small edits, then exported it as a FBX file (you can open .blend files in Unity directly, but I didn't have things setup correctly, so this was a workaround).

Next, I setup the scene for the gallery in Unity.  I'm using this ["Simple Camera Controller" demo from the Unity Asset Store](https://assetstore.unity.com/packages/tools/camera/simple-camera-controller-159957).  I just imported the demo scene, added my donut, and tested it to make sure I could control the camera as expected.

Then, I built the project with WebGL.  This creates a web page for viewing the project.  I setup a GitHub repo (this one) for the project and imported the Assets and Build.  I then [setup GitHub to host the build as a page](https://dev.to/dhruv194/host-your-unity-games-online-for-free-using-github-3ei8).  After giving it a few minutes to update, I could navigate to the [GitHub page to view it](https://nathanmargaglio.github.io/3D-Gallery/).

## Next Steps

From here, I'd continue creating Blender models (maybe more things to look at, scenary, some advanced stuff like rigged skeletons, etc.) and continue importing them into the Unity scene, which I'd also continue updating to make better (maybe some animations, better controls, UI, etc.).  Everytime I created a new model or updated the scene (or any asset), I'd make a new build and push the files into the GitHub repo.
