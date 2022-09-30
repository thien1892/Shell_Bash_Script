# Shell_Bash_Script Cheatsheet

# Data Cleaning and Munging on the Command Line
## csvkit
- is a suite of command-line tools
- oers data processing and cleaning capabilities on CSV les
- is developed in Python by Wireservice
- documentation: hps://csvkit.readthedocs.io/en/latest/
### 1. Install
- ```pip install csvkit```
- ```pip --upgrage install csvkit```

### 2. Converting files to csv
- documentation: ```in2csv -h```
- converting file_import to csv: ```in2csv file_import.* > file_export.csv```
- check sheet name in file_import: ```in2csv -n file_import.*```
- converting a sheet name in file_import to csv: ```in2csv file_import.* --sheet "name_sheet" > file_export.csv```
### 3. Data preview on the command line
- documentation: ```csvlook -h```
- syntax: ```csvlook file.csv```
### 4. Descriptive stats on CSV data files
- documentation: ```csvstat -h```
- syntax: ```csvstat file.csv```