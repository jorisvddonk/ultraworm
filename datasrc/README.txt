These are replacement files for RotT that still need to be built into their 
RotT-native formats, or still need to be packaged into .jars


"jgfont" directory contains RotT-native .jgfont files, plus the .ttf source used
 to generate those .jgfont files (see fonts.txt inside the jgfont folder)

"sprites" directory contains replacement images. Note that images starting with 
 "ultraworm.scaffolding" are meant to be temporary image replacement 'masters' 
 which can be transformed into actual replacement images via some kind of tool.
 For example, the "ultraworm.scaffolding.shadow.01.png" file can be used to 
 replace RotT content files containing ".shadow." in their name, by means of 
 scaling the scaffolding image to the wanted ".shadow." image.
 
 I (Megagun) currently have such a tool, but it's crappy and needs a tad of
 polish before I'll put it in the repos (it currently doesn't use the .xml files
 in our priject, but instead just iterates through all files in a specific
 folder somewhere on my harddrive. These files are all images I've extracted
 from the retail content. I'll need to rewrite the tool to use the .xml files). 
 :)