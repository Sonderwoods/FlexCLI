# FlexCLI
This repository contains a C++/CLI interface - called FlexCLI - for the physics engine NVidia Flex. This enables the user to access Flex' functionality from .Net environments. Furthermore the repository contains an implementation of FlexCLI in the form of a plugin for Grasshopper in Rhino3D. This plugin - called FlexHopper - provides the possiblity to use NVidia Flex physics simulation - via the FlexCLI pipeline - in the CAD software Rhino.<p>
FlexCLI is built against NVidia Flex release 1.1.0. NVidia Flex is patented property of NVidia. The author of this repository did not create or change NVidia proprietary code, nor is he the author of any code contained in the folder FlexCore110. The author of this repository is the author of FlexCLI and FlexHopper, both of which are found in the respective folders. The code inside the directory FlexCore110 is part of the NVidia Flex engine and included here to make FlexCLI usable. For more information on NVidia Flex go here: https://developer.nvidia.com/nvidia-flex-110-released<p><p>

FlexCLI runs on x64 architectures only.<p>
Flex.sln contains FlexCLI and FlexHopper. Upon building the solution all relevant files will be stored inside "bin". Make sure to set your compiler to x64.<p>
FlexHopper was tested with Rhino5 64bit and Grasshopper 0.9.0076 WIP
