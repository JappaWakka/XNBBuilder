# XNBBuilder

## About (Idea)
Converts various file formats to .xnb files for use in games made with the XNA and MonoGame frameworks, including models, audio and images.

### Update by JappaWakka:
I made it so that when the Compress Content setting is disabled, textures (including those from models) won't be compressed with DXT.
DXT Compression doesn't allow for textures with a resolution of less than 4 on either axis.
This previously meant that this tool couldn't convert models made with MagicaVoxel, of which the model textures are 1px in height.
Textures like this can now be converted to XNB too.

## Screenshots
![](Images/shot1.png)
![](Images/shot2.png)

## Format Details
* Full list of supported filetypes:
- Graphics Files: *.bmp;*.dds;*.dib;*.hdr;*.jpg;*.pfm;*.png;*.ppm;*.tga
- Autodesk FBX Files: *.fbx
- Effects Files: *.fx
- SpriteFont Files: *.spritefont
- X Files: *.x
- XNA XML Files: *.xml
- Audio Files: *.mp3;*.wav;*.wma
- Video Files: *.wmv

## Progress
I (JappaWakka) do not plan to update this tool further, as I would purely use it for model conversion.
The original creator (mediaexplorer74) of the tool doesn't seem to respond so I'm not sure if they will either.
Anyways, this version might be preferred over the original if you're trying to convert MagicaVoxel models like me.

## Caution / Warning 

The *full version* of XNA Game Studio (GS) is *required* for conversion with this software!
Please install XNA GS special edition that located at XnaForVS2022 folder (zipped XnaForVS2022.zip file can be found at Releases zone). 

To do whole setup process of GS, you need to perform *all steps* 1-5 
(see XnaForVS2022/README.TXT included , for details) .

## Additional Info
- Support for some filetypes may be incomplete, graphics filetypes should all be fine.
- If there's an issue with converting a certain filetype, let me know. I barely have any knowledge of C# but I could try to figure it out.

## References
https://sourceforge.net/projects/xnbbuilder/ XNB Builder "Web Storage" 

## ..
As is. No support. RnD only.

## .
[m][e] 2023
