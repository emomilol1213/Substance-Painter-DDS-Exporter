A Substance Painter DDS export plugin to automate the PNG to DDS conversion.

No more spending minutes converting those 20 different maps to DDS via PS/Intel/Paint.net etc

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

# Dependencies:
Microsoft Texconv (Download and extract to whatever folder you want)

https://github.com/Microsoft/DirectXTex/wiki/Texconv

# Compability
Developed and tested with Substance Painter 7.3.1 (2021)
