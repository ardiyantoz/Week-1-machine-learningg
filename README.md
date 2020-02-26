# Week-1-machine-learningg
    
#!/usr/bin/env python
# coding: utf-8

import pandas as pd

dataListing = pd.read_csv("listings.csv")

print(dataListing)

maxVal = dataListing.max()
print(maxVal)

minVal =  dataListing.min()
print(minVal)

newDataDrop =   dataListing.dropna()
print(newDataDrop)

newgDataFill =  dataListing.fillna('thisIsNULL')
print(newDataFill)
