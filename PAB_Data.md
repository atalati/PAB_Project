# PAB_Project
############ MODULE IMPORT ##############

import os
import numpy as np
import pandas as pd
from pandas import Series, DataFrame


############ DATA IMPORT ##############


os.chdir('D:/School/CMDA 3654 (Intro to Data Analytics & Visualization)/Project')
os.getcwd()

xlsfile = pd.ExcelFile('PAB Ticket Sales.xlsx')
xlsfile
type(xlsfile) #shows the type of file

BalletDF = xlsfile.parse('Ticket Sales - Name Address Rep') # name of the sheet - this reads it as a data frame
BalletDF.head()

############ DATA CLEANING ##############



