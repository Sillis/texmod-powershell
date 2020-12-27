# texmod-powershell
Powershell snippet to run to delete all normal and specular maps from texture extraction dumps, leaving only diffuse and glow maps. Can be easily changed to include other types. 

Logic: "delete all files that end in _n or _s and have the extension .dds, recursively in this folder and all subfolders, including hidden and read-only files". 

Includes WhatIf so you can preview the changes to be made.
