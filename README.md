# K-Value_Plots
## Objective:
This code plots field hydraulic conductivity (K) values onto the theoretical range of hydraulic conductivity and permeability values (after Freeze & Cherry's [1979])

Source: 
1) http://hydrogeologistswithoutborders.org/wordpress/wp-content/uploads/Freeze_and_Cherry_1979-smaller.pdf (Table 2.2)
2) https://books.gw-project.org/hydrogeologic-properties-of-earth-materials-and-principles-of-groundwater-flow/chapter/hydraulic-conductivity-values-for-earth-materials/

## Input Data:
* heoretical Freeze & Cherry's (1979) Hydraulic Conductivity Range (BasePlot Rock): *georock.csv*
* Field/Aquifer Test Data: *AQT_KValues.csv*

## Output:
![K_Plot1](https://user-images.githubusercontent.com/82328087/197513018-f16c010a-42ad-4272-b897-66a6a585ba8c.png)

## Requirements:
* Pandas
* Numpy
* Matplotlib
