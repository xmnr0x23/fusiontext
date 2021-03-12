# FusionText

FusionText is a node based string library for Blackmagic Design Fusion.

## Acknowledgements

- Kristof Indeherberge
- Cédric Duriau

## Installation

1. Clone or download the repository.
2. Set the absolute path of the **./fusion** directory into the Fusion
   **UserPaths:** path mapping.

## Contents

**Fuses**

- `textcasealternate.fuse`: Fuse to alternate the case of a Fusion Text object.
- `textcaseinvert.fuse`: Fuse to invert the case of a Fusion Text object.
- `textcaselower.fuse`: Fuse to change the case of a Fusion Text object to lower.
- `textcaserandom.fuse`: Fuse to change the case of a Fusion Text object to random.
- `textcasesentence.fuse`: Fuse to change the case of a Fusion Text object to sentence.
- `textcasetitle.fuse`: Fuse to change the case of a Fusion Text object to title.
- `textcaseupper.fuse`: Fuse to change the case of a Fusion Text object to upper.
- `textcompfilename.fuse`: Fuse that returns the full path of a comp.
- `textcompname.fuse`: Fuse that returns the name of the comp.
- `textcreate.fuse`: Fuse to create a Fusion Text object.
- `textdecodeurl.fuse`: Fuse to url-decode a Fusion Text object.
- `textencodeurl.fuse`: Fuse to url-encode a Fusion Text object.
- `textformat.fuse`: Fuse to format strings in a template string.
- `textfromarray.fuse`: Fuse to create a Fusion Text object from an array.
- `textfromfile.fuse`: Fuse to create a Fusion Text object from a file.
- `textfrommetadata.fuse`: Fuse to create a Fusion Text object from metadata.
- `textfromnumber.fuse`: Fuse to convert a number to text.
- `textlength.fuse`: Fuse to return the length of a string.
- `textmultiline.fuse`: Fuse to concatenate individual Text strings into a multi-line Text object.
- `textorderreverse.fuse`: Fuse to reverse the order of a string.
- `textordershuffle.fuse`: Fuse to shuffle the order of a string.
- `textsubformat.fuse`: Fuse to 
- `textsubjoin.fuse`: Fuse to 
- `textsubreplace.fuse`: Fuse to 
- `textsubreturn.fuse`: Fuse to 
- `textsubsplit.fuse`: Fuse to 
- `textsubstripleft.fuse`: Fuse to 
- `textsubstripright.fuse`: Fuse to 
- `textswitch.fuse`: Fuse to 
- `texttimespeed.fuse`: Fuse to 
- `texttimestretch.fuse`: Fuse to execute time based operations on text.
- `textwirelesslink.fuse`: Fuse to

**Modules/Lua**

- `textutils.lua`: Core module for string operations.
