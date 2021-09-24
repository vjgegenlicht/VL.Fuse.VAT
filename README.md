# VL.VATFuse
Examples for Vertex Animation Textures inside VL.Fuse

Fuse is an open source library for visually programming on the GPU, built to enable rapid workflows and modular approaches to accelerated graphics, logic and computation. https://github.com/TheFuseLab/VL.Fuse It is built for use in vvvv gamma ( https://visualprogramming.net/ ) and follows its "always runtime" model allowing for fast design and programming work with no build or compile process in between you and your results.

Based on SideFX Houdini GameDevelopment Toolset: https://github.com/sideeffects/GameDevelopmentToolset/blob/Development/unity
using examples from keijiro's Unity implementation https://github.com/keijiro/HdrpVatExample 

The main goals for this package is to provide examples for the most common VAT and Pivot Painter implementations used by Unreal und Unity. 

The next steps:

1. Getting it to work with the Fuse PBR Pipeline
2. Create examples for Epics unreal tools  - Blender VAT Exporter Plugin https://github.com/JoshRBogart/unreal_tools
3. Various blender Pivot Painter Plugins
4. Unpack Normals from alpha
5. Clean up everything to a nice set of Fuse functions

Installation: 

1. Copy or Clone to your VL Nuget folder ( %appdata%\Local\vvvv\gamma-preview\nugets\ ) 
2. Open VL Gamma, latest preview and latest VL.Fuse nuget installed: Guide -> https://www.youtube.com/watch?v=25sk7_NaEgM&t=15s
3. Press F1 to open the help browser
4. search for VATFuse to see the example patches...
