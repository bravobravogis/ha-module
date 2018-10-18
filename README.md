# module
Module for import during mapping

## Synopsis
A collection of functions designed to simplify routine mapping operations, from label expressions to feature class manipulation. Each can be applied during field calculations, label expressions, toolbox scripts, or from within the Python window itself.

There are currently twenty (20) functions, grouped as follows:

1. String Formatting  
  +**clean_name**: format text to remove non-standard characters  
  +**ac**: add color  
  +**ab**: add bold  
  +**ai**: add italics  
  +**au**: add underline  
  +**exceed_mcl_ca**: bold values with California MCLs exceedance  
  +**exceed_mcl_epa**: bold values with federal (EPA) MCLs exceedance  
  +**exceed_esl_gw**: bold groundwater values with California Tier 1 ESLs exceedance  
  +**exceed_esl_soil**: bold soil values with California Tier 1 ESLs exceedance  
  +**exceed_esl_ss**: bold subslab/soil gas values with California Tier 1 ESLs exceedance  
  +**exceed_esl_ia**: bold indoor air values with California Tier 1 ESLs exceedance  

2. Feature Class Modification  
  +**attach_coords**: add fields for coordinates and update  
  +**add_fields_line**: add fields to line feature class  
  +**add_fields_point**: add fields to point feature class  
  +**add_fields_poly**: add fields to polygon feature class  
  +**update_id**: add field and updates ID by specified incremental amount  
  +**update_id_nwse**: add field and updates ID based upon northwest to southeast position  
  +**update_id_nesw**: add field and updates ID based upon northeast to southwest position  
  +**update_id_swne**: add field and updates ID based upon southwest to northeast position  
  +**update_id_senw**: add field and updates ID based upon southeast to northwest position  

## Motivation
The ability to import a module, with a collection of custom functions, makes routine mapping activities more efficient. As with toolboxes, modules can be easily shared amongst members of an organization. Maps constructed using shared modules are consistent, and reliance upon Python will encourage further growth and learning.

With appropriate documentation and controls, modules can be updated to include routines specific to the needs of a client. Similarly, modules can include analysis and processing specific to the needs of a project. Once constructed, the module can be relied upon again and again.  

## Installation
Download the custom module and extract the .py file to the following folder:\
_C:\Users\<user name>\AppData\Roaming\ESRI\Desktop<version number>\ArcToolbox\My Toolboxes_

## Contributors
Ian Bruce is the sole contributor (as of *October 18 2018*).
