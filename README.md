# The KAOS Toolkit (Prototype)

The KAOS Toolkit is a set of tools for use in development of applications for the Color Computer 3. The main focus of the prototype tools is to explore the details of converting and compiling of various multimedia assets into a format usable in retro computer game development. The Toolkit release currently includes three of the primary command line based tools; a palette converter, a general texture converter, and a texture compiler.

### KAOS Palette Processor (KAOSPP)
The Palette Processor loads GIMP format palette files, checks the color values, and converts them to xxRGBRGB format, and generates an assembly language file containing a series of FCB statements that can be sent to the TC1014 (GIME) palette registers. 

### KAOS Texture Processor (KAOSTP)
The Texture Processor provides basic features for converting a wide range of modern and Color Computer 3 specific image formats to a raw uncompressed image file. The texture processor can load and convert BMP, GIF, JPEG, PBM, PNG, TIFF, TGA, WEBP, MGE, VEF, CM3, and RAT image file formats.

### KAOS Texture Compiler (KAOSTC)
The Texture Compiler, commonly referring to as a sprite compiler, loads and converts image files in much the same way the Texture Processor does except that it generates directly executable Motorola MC6809 assembly language to draw the texture. The Texture compiler supports all image formats allowed by the Texture Processor plus the Piskel multi-frame sprite format.

