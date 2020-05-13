# Data-Generator-Febrl-
https://sourceforge.net/projects/febrl/

Run generate2.py by command "python2 generate2.py ...(the required parameters which need to be set as input)"
As the code is based on python 2, do not directly use command "python ... " if your python version is python 3. 

Example:
python2 generate2.py 10000.csv 4000 6000 9 4 6 uniform all 0 

The meaning of these parameters (parameters after generate2.py) are as follows:
  - Output file name
  - Number of original records
  - Number of duplicate records
  - Maximal number of duplicate records for one original record
  - Maximum number of modifications per field
  - Maximum number of modifications per record
  - Probability distribution for duplicates (uniform, poisson, zipf)
  - Type of modification (typo, ocr, phonetic, all)
  - Number of households and family records
