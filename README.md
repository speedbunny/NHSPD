# NHSPD - Human Readable Lookup of the NHS UK Postcode Data
# Extract Postcode Information from NHSPD dataset (on GOV UK)
# Download location Office for National Statistics data - NHS Digital
# https://digital.nhs.uk/services/organisation-data-service/data-downloads/office-for-national-statistics-data
# V1.0 - 140521 - Sarah Eaglesfield

#    ****     USAGE  ****
#1. Extract the Data from NHS Postcode Download above /m
#2. Modify script to suit your needs ensuring paths and lookup tables are correct  /m
#3. Run - it will produce a CSV of the output in the output folder  /m

#   ****     INSTRUCTIONS  ****
#There are 41 columns of data in the dataset. These are detailed on P27-P40 the User Guide PDF. 
#To Add An Additional Column 
#1. Download the corresponding lookup table from the above URL
#2. Change the col_type from col_skip to its actual type given in comments on the sam line
#3. Add the file location to the fnames list

#   ****     TROUBLESHOOTING  ****
#1. Make Sure The Path of the Filename is Set Correctly Relative to the Base Directory for R
#2. Some NHS Lookup Tables have 3 columns - drop the unneeded column on an adhoc basis
