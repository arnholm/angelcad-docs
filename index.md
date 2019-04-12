**AngelCAD - script based 3D solid modeller**

AngelCAD is an open source 3D solid modeller based on the Constructive Solid Geometry [CSG](https://en.wikipedia.org/wiki/Constructive_solid_geometry) modelling technique and the [AngelScript](http://www.angelcode.com/angelscript/sdk/docs/manual/doc_script.html) scripting language. Use AngelCAD to create 3d models in STL or other formats.


<script src="https://embed.github.com/view/3d/arnholm/acdocs/master/stl/csg_wikipedia.stl?height=300&width=500"> </script>
The csg_wikipedia.as sample



| AngelCAD resources |   |
| :---------------------------- | : --------- |
| [language reference](/docs/index.html){:target="_blank"}  | AngelCAD scripting language reference  |
| [angelcad-samples](https://github.com/arnholm/angelcad-samples){:target="_blank"}  | AngelCAD examples repository - GitHub |
| [downloads](https://github.com/arnholm/xcsg/releases){:target="_blank"} | Executable binaries - Windows and Linux |

(links above open in new tabs) 



**AngelCAD IDE and Viewer** - With the desktop IDE you edit/run the scripts and launch the 3d Viewer

![AngelCAD modeller](/images/angelcad_ide.png)


**Technology** - AngelCAD uses [xcsg](https://github.com/arnholm/xcsg){:target="_blank"} for 3d computations. xcsg is based around the [carve library](https://github.com/arnholm/carve){:target="_blank"} created by Tobias Sargeant. xcsg also uses qhull by C.B. Barber and libtess2 by Mikko Mononen.

The AngelCAD language interpreter - as_csg - is based on the ecellend [AngelScript language](http://www.angelcode.com/angelscript/) by Andreas Jönsson. as_csg extends the language with 3d modelling types and operations.

The AngelCAD IDE and Viewer applications uses the [wxWidgets cross-platform GUI library](https://wxwidgets.org/) to create native GUI applications for Windows and Linux.
