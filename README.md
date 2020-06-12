# FracRough_github
 FracRough—Computer Program to Calculate Fracture Roughness from Reservoir Rock Core
 

**************************************************  
NAME OF CODE:			FRACROUGH
DEVELOPER:				Sait I. Ozkaya
email: 				saitozkaya@ gmail.com
mob: 				90 537 283 7243
273 3 943 7071
HARDWARE:				PC
SOFWWARE:				WINDOWS, Microsoft Excel platform
PROGRAMMING LANGUAGE:		VBA
YEAR:					2020
TEMPLATE:				FRACROUGH JRC EXCEL VBA.XLSM
****************************************************  
HIGHLIGHTS
Fracture roughness has many applications in engineering and petroleum geology.
Fracture roughness measurement on cores from subsurface rocks is a challenge.
FRACROUGH software is designed to calculate fracture roughness from cores
Input consists of fracture traces from core, borehole diameter and attitude
Output is Joint roughness coefficient, JRC and wall mismatch for each fracture.

INSTRUCTIONS

Copy the template ROWS 1 TO 6 to a new spreadsheet	
Fill in the parameters (B1-B5)
Arrange input data as in the example set n the template (Columns 1 and 2)
Make sure each fracture trace x y data are preceded by a negative number indicating the sequence number for the fracture in column 1 and  "base" or "top" word in column 2
Place x and y data in x sequence increasing or decreasing order	
Place a large negative number "end" instead of "base" or "top" after the last fracture trace i.e. -1000 end

Each fracture must have base and top. If one is missing the program will calculate JRC values but give an error message and stop when calculating mismatch between top and bottom traces

Click the blue icon to run the program {wait for a short while if the screen goes blank}

The intermediate results for JRC calculation are in columns D to I for plotting purposes and the summary table is in columns M to Z

The intermediate results for mismatch are in columns AB to AL. Mismatch summary table is in columns AN to AS. The search column for JRC is column C and for Mismatch column AM

Two example runs are included in pages 14.5 in core and 19.5 in core
