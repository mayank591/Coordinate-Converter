# Coordinate-Converter
This executable is for bulk conversion of coordinates from UTM format to Lat Lon and Lat Lon to UTM format.
#
Input File should contain the coordinates in the format as shown in example below:
#
Format for input file for Lat Lon to UTM conversion:
#
    Point Id  Latitude  Longitude Altitude
#
Note: Lat Lon should be in Degree Decimal Format
#
Format for input file for UTM to Lat Lon conversion:
#
    Point Id  Easting  Northing Altitude
#
Delimiter should be one of the following:
#
    Comma, Space, Tab, Semicolon
#
A text file containing the result of conversion will be created with given output file name or with given input file name (if output file name is not given) in the same folder as that of input file. 
