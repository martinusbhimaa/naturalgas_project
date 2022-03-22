# **Natural Gas Engineering Projects**

## **Description**
Natural gas is a naturally occurring mixture of hydrocarbon gases that is highly compressible and expansible, mostly consisting of methane and other light components. This project is related to natural gas reservoir engineering and production engineering problems. Natural gas characteristic is not similar with crude oil reservoir and production, thus yields a different case and solution.
## **Project**
The projects include PVT and fluid characterization of natural gas, in-place estimation using probabilistical and analytical method, gas well testing, and production performance parameter for natural gas reservoir.

## **a. Project 1 & 2: Gas PVT Characterization**
### **Description**
In the first project, you are required to compare Z factor calculated from Peng-Robinson (PR) Equation of State (EOS) and common equation (e.g Beggs-Brill Correlation). *File name: prEOS, GasPropCalc, and PlotProp*
### **Requirements**
Component fractions are needed and pseudo properties have to be well defined. Pressure and temperature in reservoir condition have to be the input as well. These data will be sufficient to run this code.
### **Results**
PVT profile includes gas density, formation volume factor, gas deviation factor, and gas viscosity. You can see a profile plot and single value on certain pressure and temperature as well.

## **b. Project 3 & 4: IGIP Estimation**
### **Description**
In-place estimation using probabilistic which is Monte-Carlo simulation and analytical method using material balance formulas which are p/Z and F vs Eg. *File name: monteSim, gasMbal*
### **Requirements**
For probabilistcal method, variables such as area, net thickness, water saturatiom, porosity, and gas formation volume factor distribution have to be defined and type of distribution as well (e.g triangular, normal, etc.). For analytical method, you need to have **pressure vs cummulative gas production data** and also **Z factor data** as function of pressure.
### **Results**
IGIP distribution can be calculated and classified as P90, P50, and P10. Histogram feature is also provided to see the distribution plot of each class. Once IGIP is distributed, IGIP from MBAL method has to be in range in IGIP distribution. One IGIP value from p/Z vs Gp and F vs Eg can be determined and curve fitting plot between calculated model and known data. 

## **c. Project 5 & 6: Gas Well Testing and Well Performance**
### **Description**
In this project, you can process gas well testing data (e.g backpressure test, isochronal test, and modified isochronal test) to determine maximum well potential, skin, and turbulence factor using pressure-squared and pseudo-pressure method. *File name: skin_turbulence, aofp*
### **Requirements**
Like the previous projects, gas properties need to be calculated first, especially for Z factor and gas viscosity. **More importantly**, you are required to have pressure test data (time in hrs and Pressure in psia) and flowrate test (time in hrs and Gas Rate in Mscfd).
### **Results**
Absolute Open Flow (AOF) potential, skin factor, and turbulence factor can be determined to examine production performance from gas well and these values are very important to become the input on reservoir simulation. You also can compare both methods; Pressure squared and pseuode-pressure and which method that has an more optimistic value. 