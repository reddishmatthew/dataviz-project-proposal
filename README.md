
# Data Visualization Project

## Data

The data I propose to visualize for my project is a history of [Meteorite Landings](https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh/about_data).

The dataset records historical meteorite landings since the year 1880 and the geolocations of their landings, supplied by NASA. 


## Questions & Tasks

1. **GeoLocation Accurate Landings of Each Meteorite**

   - Visualize the latitude and longitude accurate locations of the landings
    of each meteorite. Displaying with opacity the the areas with higher and
    lower effect.

2. **Compare the sizes of the meteorites.**

   - Using varying size that are relative to the mass (g) of each meteorite
     to compare the sizes of each impact.

3. **Chronological Order of Landings.**

   - Display a year counter that works in unison with the animation.
     Throughout the visualization the landings will be displayed
     one by one in consecutive order. Fading out after a period of time
     to reduce clutter.

4. **Display the Class Types of Meteorites.**

   - Visualize through hue the varying classifications of meteorites.
     This will display the common and less common classes.

5. **Compare Meteorite Size and Class Type.**

   - Using both the hue to visualize class types and size to display
     the mass of each meteorite relatively, it will visualize the
     correlation between class and size. 

## Sketches

![image](IMG_6679.jpg)

Above is my sketch that displays how the general look will be. Notice the world map decorated in the background
to visualize rough location of landing. The world map will fill with circles to display the meteorites.

![image](ApplicationFrameHost_C9rAl5h2MM.png)

This is a more detailed depiction of the previous sketch. Notice the bars that display latitude and longitude.
The map will be to real scale coordinates. 
The circles are of different sizes and color to display the mass and class type.

![image](SecondImage.png)

This shows the interactability within the visualization. When clicking on a meteor, it will display the 
data correlated to it. Showing the categories "Name, Class, Mass (g), Year, GeoLocation" that are 
supplied by the dataset.

![image](ThirdImage.png)

This image shows a comparison factor. When double clicking on another meteorite the two will be side 
by side for easy comparison. In the future I may implement a 'difference' factor that shows how much
more or less tha mass, year and GeoLocation is to the other.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatterplot and it shows the latitude
and longitude accurate map of the world with historical data of meteorite landings. Each dot represents 
a landing, but currently does not show when they landed, what class they are and their mass.

[![image](Visualization.png)](https://vizhub.com/reddishmatthew/landings-scatterplot)

Click on the image to be sent to the VizHub.

## Milestones

  -  **Week 8:** Create the world map and change the sizes of the data points by mass.
  -  **Week 9:** Change the hue based on the class type. Add a year counter.
  -  **Week 10:** Animate the data points to enter one at a time, year counter follows.
  -  **Week 11:** Add a second animation so the data points fade once a maximum amount of data points shown is reached.
  -  **Week 12:** Create a mouse click interaction to display data.
  -  **Week 13:** Create a comparison tool that expands on the mouse click interaction.
  -  **Week 14:** Finalize and report.
