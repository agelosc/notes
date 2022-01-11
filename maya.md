#### Resize Image in Maya
```
# Python code:
import maya.OpenMaya as om

def resizeImage(sourceImage, outputImage, width, height):

    image = om.MImage()
    image.readFromFile(sourceImage)

    image.resize( width, height )
    image.writeToFile( outputImage, 'png')


resizeImage('<sourceImage.png>','<outputImage.png>', 800, 600)
```
