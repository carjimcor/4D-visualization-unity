# Unity 4D visualization

3D + t representation of a 4D boolean matrix. True represents a cube, False represents empty.

Matrix size = 20 x 20 x 20 x 20 (x,y,z,w).

On each frame, the big white wireframe box contains a 3D representation of the 4D matrix given a 'w' (4th coordinate).

## Demos

![Demo random spheres](https://raw.githubusercontent.com/carjimcor/4D-visualization-unity/master/readme%20images/demo_1_esferas.gif)
Random Spheres

![Demo random points](https://raw.githubusercontent.com/carjimcor/4D-visualization-unity/master/readme%20images/demo_2_aleatorio.gif)
Random 4D points

## Requisites

* [Unity 2017.3.1f1](https://unity3d.com/es/get-unity/download/archive) (or maybe more)

This project uses Unity's debug system ['OnDrawGrizmos'](https://docs.unity3d.com/ScriptReference/MonoBehaviour.OnDrawGizmos.html) function, which can only be used inside the editor. So there is no point in building the project since that feature can't be used outside the editor.

## Instructions

1. Download the 'PID.7z'.
2. Extract it.
3. Open it using Unity.
4. Hit play on top of the editor.
