## QuickMeasure Addon

Quick Measure is a FreeCAD tool designed to measure features quickly without needing to add dimensions to the graphic’s window.

## Screenshots
![QMeasure](https://user-images.githubusercontent.com/42722171/201226021-079560d0-d55b-42f7-b4e5-49e8dd876f62.jpg)
## Installation

QuickMeasure addon is available via the FreeCAD Addon Manager.

* Run FreeCAD [Addon Manager](https://wiki.freecad.org/AddonManager).
* Install QuickMeasure addon.
* Restart FreeCAD.

## Usage

* Select Quick Measure from the [Workbench dropdown](https://wiki.freecad.org/Std_Workbench).

<img src="img/workbench_select.jpg" alt="workbench-select" width="900"/>

* Launch the tool by clicking on the Quick Measure icon. This will luanch the dialog window that will display info as you select items in your design.

<img src="img/tool_icon_select.jpg" alt="tool-icon-select" width="900"/>

* Selecting a vertex from the graphic window will result in the x, y, z position of the vertex being shown in the dialog. 
* Selecting a line will also show its length, a Sphere shows the radius, a cylinder the radius plus the length.
* Selecting two features will show the distance between them plus, when applicable, the distance in x, y and z axis. Lines and cylinders show if they are parallel or not.
* Selecting three or more surfaces together adds the areas of the surfaces together.

## Developer

Dan Miel ([@DanMiel](https://github.com/DanMiel))

## License

GPLv3 ([LICENSE](LICENSE))
