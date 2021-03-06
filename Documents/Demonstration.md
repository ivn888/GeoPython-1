## Demonstration of the Functions


## Open and Import Data
To start a plot or calculation, raw data file should be imported to GeoPython first.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/ImportData.png)


The Data file can be Xlsx/Xls or CSV.
![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/ChooseAndImport.png)

## Set Up Data

If there is no setting up information such as the Label/Color/Marker/Style/Alapha/Width, you need to click on the Set Format button to add these items and make modification by yourself.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/SetDataUp.png)

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/SettingDataUp.png)


## Click the Function you need

After setting up, you can just click to use the function you need.
![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/ClickOnTheFunction.png)

## TAS/REE/Trace Elements

These functions are quite commonly used and the details are shown as the picture below.
![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/TAS-REE-Trace.png)


## Pearce Diagram

Pearce Diagram just use some trace elements and is also quite easy to know how to use.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/Pearce.png)

## Harker Diagram

Harker Diagram is a little bit complicated. Both the X and Y items used for the picture can be selectable by the slider.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/Harker.png)

## QFL and QmFLt

These two diagrams are very easy. But you must find the right data file used for them to import.
![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/ImportQFL.png)

Remind to set up data, then you can run these two functions.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/QFLandQmFLt.png)

## Stereographic Projection and Rose Map

Wulf or Schmidt Net can be chosen, and so is to use Lines or Points on the generated diagram.
In the Rose Map function, all data in one data files can be treated as a single group of data to draw Rose Map, and can also be treated as seperated teams to compare the Rose Map from each other. The step of the Rose Map can be set by slider. And so does the items chosen to use in the Rose Map. Dip/Dip-Angle/Strike are all available.

Notice that the first Letters must be in UPPER case.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/StereoAndRose.png)

## Zircon Ce4/3 Ratio Calculation

The data file used here is quite complicated. Please follow the guidance shown in the picture below.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/ZriconCeCalculation.png)


## Zircon and Rutile Thermometer

These two function are super easy. Notice the ASiO2 and ATiO2 here are the Activity of these two components.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/Thermometer.png)




## User Defined X-Y plot

This function allows users to load any picture from any articles as a base map to plot on.

But you must understand the original plot first and know the mathematical setting of it. So you can set up the right format in your plot.

For example, as the picture below shown,  the original diagram used Nb and Th, normalized by N-MORB(Sun and McDonough 1989), and then used the Log function of these two items. So we do the same setting up as shown by the picture. The Left/Right/Down/Up limit of the original diagram are 0.01/100/0.01/1000, so we need to use the Log function and find out that we should set the Left/Right/Down/Up limit to be -2/2/-2/3. If you can not understand why, please take a rest and good bye.

![](https://raw.githubusercontent.com/chinageology/GeoPython/master/img/UserDefinedXY.png)


