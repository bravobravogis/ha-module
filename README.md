# ha-module
Module for import during mapping

## Synopsis
A collection of functions designed to simplify routine mapping operations, from label expressions to feature class manipulation. Each can be applied during field calculations, label expressions, toolbox scripts, or from within the Python window itself.

There are currently eight (8) functions, grouped as follows:

1. String Formatting  
  +**clean_name**: format text to remove non-standard characters  
  +**ac**: add color  
  +**ab**: add bold  
  +**ai**: add italics  
  +**au**: add underline  

2. Feature Class Modification  
  +**add_fields_point**: add fields to point feature class  
  +**add_fields_line**: add fields to line feature class  
  +**add_fields_polygon**: add fields to polygon feature class  

## Motivation
The ability to import a module, with a collection of custom functions, makes routine mapping activities more efficient. As with toolboxes, modules can be easily shared amongst members of an organization. Maps constructed using shared modules are consistent, and reliance upon Python will encourage further growth and learning.

With appropriate documentation and controls, modules can be updated to include routines specific to the needs of a client. Similarly, modules can include analysis and processing specific to the needs of a project. Once constructed, the module can be relied upon again and again.  

## Installation
Download the custom module and extract the .py file to the following folder:\
_C:\Users\<user name>\AppData\Roaming\ESRI\Desktop<version number>\ArcToolbox\My Toolboxes_

## Contributors
Ian Bruce (Haley & Aldrich, Inc.) is the sole contributor (as of *14 June 2018*).
