# How to Install (for Unity)

## Requirements

I recommend you use the fbx file but you can use either the blend or fbx file in your Unity project. However the blend file requires Blender to be installed on each development machine.

## Manual

1. Download and copy [shapes.fbx](Assets/Homu-Shapes/Shapes.fbx) from the Assets/Homu-Shapes folder
2. Paste it anywhere into your project's Assets folder
3. Make sure `Use File Scale` is enabled in the file's import options

## Unity Package Manager (remote)

* Not yet supported by Unity.

## Unity Package Manager (local)

1. Download the [Homu-Shapes](Assets/Homu-Shapes) folder onto your machine
2. Navigate to your Unity project's Package folder
3. Open the manifest.json file
4. Add the line `"com.wakabagames.homu-shapes": "file:<YOUR FILE PATH HERE>"`
5. Change the file path so it points to the root of your `Homu-Shapes`' folder
6. The file path is relative and you can use `..` to go up a folder
7. E.g. `"com.wakabagames.homu-shapes": "file:../../Homu-Shapes/Assets/Homu-Shapes"`
8. Alternatively you can use an absolute path.
9. E.g. `"file:C:\\Users\\Lemon\\Documents\\Github\\Unity\\Homu-Shapes\\Assets\\Homu-Shapes"`