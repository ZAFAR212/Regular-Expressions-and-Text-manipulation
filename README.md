# Regular-Expressions-and-Text-manipulation
This is an algorithm I wrote to allow me to align name formatting where names to a single skype format: LASTNAME, FIRSTNAME. 

The script will try to detect and remediate 9 different types of cases. Although the script could be shortened further, for debugging purposes, I kept it as it is.

Cases:

1) FIRSTNAME LASTNAME instead of LASTNAME, FIRSTNAME
2) LASTNAME,FIRSTNAME (no space)
3) contains AND or /
4) contains brackets
5) Numbers
6) email addresses
7) This case included patterns of 2 people being assigned a single contract. However, some erroneous cases included the same persons name before and after a semi colon
8) The last case is similar to the above but in this case, the formats before and after the semi colon were not the same and it may not necessarily be the same person before and after the semi colon.

Some people may share the same names but may be 2 different people. We follow skype's format by assigning them a number e.g. 1 or 2.

