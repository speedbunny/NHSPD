# NHSPD - Human Readable Lookup of the NHS UK Postcode Data
### Extract Postcode Information from NHSPD dataset (on GOV UK)
### Download location Office for National Statistics data - NHS Digital
### https://digital.nhs.uk/services/organisation-data-service/data-downloads/office-for-national-statistics-data
V1.0 - 140521 - Sarah Eaglesfield

#    ****     USAGE  ****
#1. Extract the Data from NHS Postcode Download above <br>
#2. Modify script to suit your needs ensuring paths and lookup tables are correct <br>
#3. Run - it will produce a CSV of the output in the output folder <br>

#   ****     INSTRUCTIONS  ****
#There are 41 columns of data in the dataset. These are detailed on P27-P40 the User Guide PDF. <br>
#To Add An Additional Column <br>
#1. Download the corresponding lookup table from the above URL<br>
#2. Change the col_type from col_skip to its actual type given in comments on the sam line<br>
#3. Add the file location to the fnames list<br>

#   ****     TROUBLESHOOTING  ****
#1. Make Sure The Path of the Filename is Set Correctly Relative to the Base Directory for R<br>
#2. Some NHS Lookup Tables have 3 columns - drop the unneeded column on an adhoc basis
