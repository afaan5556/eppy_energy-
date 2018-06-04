# eppy_energy-

## Introduction
*This script could run EnergyPlus parametrically with Eppy package( [Eppy tutorial link](https://pythonhosted.org/eppy/Main_Tutorial.html)), generating new IDF files with different orientations in folder "idfs".
*This script also solves problems when automatically deploying one building IDF model to a large amount of different locations with loops of replacing the ddy information in IDFs and attaching epw files to run.
*information in ddy file is extracted and used to replace the "sizing period" part in IDF files with Regex package([Regex Doc](https://docs.python.org/3/library/re.html)).
*All the weather files in the database(.epw and .ddy) are downloaded and stored in folder "weather". The locations need to run (weather file names without extensions) are listed in the WeatherFileNameList.csv file under "runtrial". This csv file could be written by reading the weather file name list in the weather directory with function "WriteEPWNameToCSV" or manually edited by entering the weather file name.
*The results of simulations would be stored in folders generated in "runtrial" repository.


## Heading 2
This is where I will describe variables and paths

### Heading 3
This is where I will describe functions

### Heading 3
THis is where I will describe loops

