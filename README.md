# Visualization of Laser Induced Plasma Temperature

[The live version is available here!](https://ageller.github.io/IDEAS_FSS-Vis/FinalStudentProjects/2020summer/SumanBhandari/)

<div style="text-align: justify">
  <br>  
This visualization project shows how the temperature within the plasma changes with time and distance from the center of the plasma plume. Laser-Induced Plasma Micromachining (LIPMM) has the ability to machine deeper features compared to direct laser ablation. In the LIPMM process, a workpiece is immersed on a dielectric and a high-power pulsed laser is focused just above the workpiece surface. If the laser pulse energy is greater than the breakdown threshold of the dielectric, plasma forms through the optical breakdown of the dielectric. When this laser-induced plasma comes in contact with the workpiece, the material vaporizes due to the very high temperature of the plasma (>6000 K). The temperature of the plasma is an important factor that determines the material removal rate.

</div>


<div style="text-align: justify">
     <br>
The data is extracted from Ahmed et.al. 2008 paper titled “Spectroscopic study of laser-induced plasma in aqueous media”. The paper reports the laser-induced plasma temperature on the surface of ionic solutions of Ca++. Linear interpolation is used to create more data points at different times and distances. The Jupyter Notebook file used to generate the data points is inside the Data Generation folder.
</div>

## Interacting with the visualization

<div style="text-align: justify">
    <br>
The visualization has sliders to change the time of the plasma evolution, the size of the ball (which figuratively represents plasma constituents), and the opacity of the balls. There are also three sliders that show the cross-section of the plasma in x, y, or z-directions. Users can choose from 3 different color maps and use the mouse to drag the plasma to change the viewing angle. The users can also zoom in and out of the plasma. A plot of temperature as a function of time is also included for different distances (in microns) from the plasma.
</div>
