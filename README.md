# Template Goldsrc to Source port
This contains some goldsrc models(from halflife 2 classic), one template pre-ported model, downloads for software needed, and some help with QC files!

# Required software downloads
Decompmdl: https://twhl.info/vault/view/6799

VTFEdit: https://gamebanana.com/tools/95

.NET Framework 3.5: https://www.microsoft.com/en-us/download/details.aspx?id=21

Crowbar 0.74: https://github.com/ZeqMacaw/Crowbar/releases/download/v0.74/Crowbar_2023-02-16_0.74.7z

7-Zip: https://www.7-zip.org/

# QC File help
so when you open the QC file of your exported mdl, you will see something like this at the top:

$cd .

$cdtexture ./maps_8bit

To convert it, remove the $cd line, change $cdtexture to $cdmaterials, remove the "./" from maps_8bit and you're done converting the QC file!
