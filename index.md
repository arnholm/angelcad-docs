**AngelCAD - script based 3D solid modeller**

AngelCAD is a powerful open source 3D solid modeller based on the Constructive Solid Geometry ([CSG](https://en.wikipedia.org/wiki/Constructive_solid_geometry)) modelling technique, expressed in the [AngelScript](http://www.angelcode.com/angelscript/sdk/docs/manual/doc_script.html) language. The software creates 3D models in STL or other file formats.


<script src="https://embed.github.com/view/3d/arnholm/acdocs/master/stl/csg_wikipedia.stl?height=300&width=500"> </script>
The csg_wikipedia.as sample



| AngelCAD resources |   |
| :---------------------------- | : --------- |
| [AngelScript language](http://www.angelcode.com/angelscript/sdk/docs/manual/doc_script.html){:target="_blank"}  | AngelScript language reference  |
| [AngelCAD language extension](/docs/annotated.html){:target="_blank"}  | Language extension for 3d modelling  |
| [angelcad-samples](https://github.com/arnholm/angelcad-samples){:target="_blank"}  | Examples repository - GitHub |
| [Video](https://youtu.be/h-qDzG9bwnQ){:target="_blank"}  | script based 3D solid modeller |
| [Downloads](https://github.com/arnholm/angelcad/releases){:target="_blank"} | Prebuilt binaries - Windows and Linux |



(links above open in new tabs) 



**AngelCAD IDE and Viewer** - With the desktop IDE you edit/run the scripts and launch the 3d Viewer

![AngelCAD modeller](/images/angelcad_ide.png)


**Technology** - AngelCAD uses [xcsg](https://github.com/arnholm/xcsg){:target="_blank"} for 3d computations. xcsg is based on the [carve library](https://github.com/arnholm/carve){:target="_blank"} by Tobias Sargeant. Also used is [Clipper](http://angusj.com/delphi/clipper.php) by Angus Johnson, qhull by C.B. Barber and libtess2 by Mikko Mononen.

The AngelCAD language interpreter - as_csg - is based on the [AngelScript language](http://www.angelcode.com/angelscript/){:target="_blank"} by Andreas Jönsson, as_csg extends the language with 3d modelling primitives and operations for constructive solid geometry.

The AngelCAD IDE and Viewer applications use the [wxWidgets cross-platform GUI library](https://wxwidgets.org/){:target="_blank"} to create native GUI for Windows and Linux.
