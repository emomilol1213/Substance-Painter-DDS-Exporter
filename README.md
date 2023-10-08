<h1 align="center">
Starfield Substance Painter DDS Exporter
</h1>

![banner](https://staticdelivery.nexusmods.com/mods/4187/images/4891/4891-1696725885-1834762162.png)

# Starfield Mod Page
https://www.nexusmods.com/starfield/mods/4891

A Substance Painter DDS export plugin to automate the PNG to DDS conversion.

Mainly made for making Starfield modding easier via DDS creation, but could be tweaked in the future to be more modular and dependant on export presets.
No more spending 20 minutes manually converting those 20 different maps to DDS via tedious steps in PS/Intel/Paint.net etc

# Installation:
Extract the starfield-dds-exporter.py into your Substance Painter Plugin folder:
<pre>
C:\Users\username\Documents\Adobe\Adobe Substance 3D Painter\python\plugins
</pre>

(Can also be found using the Python > Plugins Folder button in the top row)

## Export preset:
Move the Starfield.spexp from the optional files to this folder: 
<pre>
C:\Users\username\Documents\Adobe\Adobe Substance 3D Painter\assets\export-presets
</pre>

## Enable the Starfield-DDS-Exporter under the Python menu
First time running the plugin it will ask you what folder the Texconv.exe is located in via a UI pop-up. This will create a Starfield-DDS-Exporter-PluginSettings.ini in the plugin folder with the settings saved.

![plugin widget](https://staticdelivery.nexusmods.com/mods/4187/images/4891/4891-1696725603-1907132508.png)
Dockable widget with output terminal and basic settings

# Dependencies:
Microsoft Texconv (Download and extract to whatever folder you want)

https://github.com/Microsoft/DirectXTex/wiki/Texconv

# Compatibility
Developed and tested with Substance Painter 7.3.1 (2021)

## Support
For support, please use this repository's GitHub Issues tracking service. Feel free to send me an email if you use and like the plugin.

Copyright (c) 2023 Emil Eldstål
