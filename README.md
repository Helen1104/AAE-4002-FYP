path = r'C:\Users\20062511d\Desktop/data.xlsx'  #insert the path 
import pandas as pd   

data = pd.read_excel(path)  #read the file  
print( data[['Equip.']].value_counts()) 
