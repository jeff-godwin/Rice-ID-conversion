# Rice-ID-conversion
This R package is useful for interconversion between MSU Rice Genome Annotation Project (Loc) IDs, RAP-DB (Os) IDs and NCBI IDs.
It requires R version 3.5.1 or higher.

The Input is a file with the list of IDs(RAPdb/MSU/NCBI_ID) that have to be converted.
NCBI ID will follow the format of LOCXXXXXXX

The databases are symbolised by - RAPDB - "RAP"; MSU - "MSU"; NCBI - "SYMBOL"
Based on the input given, the "fromType" and "toType" arguemnet will change in the RiceIDConvert function

Reference - https://CRAN.R-project.org/package=riceidconverter
