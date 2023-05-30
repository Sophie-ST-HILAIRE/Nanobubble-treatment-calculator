# Nanobubble treatment calculator: treatment time and costs

This is the repository to the Nanobubble treatment calculator, an app to determine the time nanobubble treatments should be applied to achieve a user specified increase in aquaculture pond water dissolved oxygen levels and/or pond water disinfection through the application of ozone nanobubbles. The cost of the treatment is also provided. User specified input is entered in the inpit panel, where predefined input values are provided, while app cost and treatment time putputs are provided in the app output section.
<p align="center">
<img width="400" src=https://github.com/Sophie-ST-HILAIRE/Nanobubble-treatment-calculator/assets/134591091/c6b652de-16ad-4eab-84d1-a73de403e28e/>
   <br>
    <em> Nanobulle treatment app input panel and outputs.</em>
</p>

## Input panel
After selecting the purpose of the nanobubble treatment, the user is asked to specify if the energy to power the nanobubbler(s) is supplied via the electric grid or if they are using a rented diesel powered generator. In the event of the electricity supplied from the grid, the price of electricity per kwh can be customized in the "Customization" section of the user input panel. If the option "Generator (diesel)" is selected, the user can specify if they are renting the generator and the rental cost per hour; diesel generator efficiency (%), the cost of fuel per liter, and the fuel energy content can be customized in the "Customization" section of the user input panel.

Nanobubblers are often coupled to ozone or oxygen generator. Three options are provided to select nanobubblers associated to ozone or oxygen generators are provided in the input parameter "Select the equipment used". These three options automatically provide the calculator with the water and electricity consumption parameters for each of the three setups. Furthermore, the user can select a fourth option in the list of equipment to customize the specifications of the nanobubbler, with or without the addition of a gas generator, in the "Customization" section. Here, the energy consumption per hour for the nanobubbler or nanobubbler and generator setup, can be specified, along with the oxygen output and equipment water flow. The number of nanobubblers, or nanobubble and generator setups, can be specified in an additional input " How many machines will you use to treat one pond?". 

The user needs to specify the pond volume in cubic meters, where one cubic meter is the equivalent to 1000 L. The app does not consider the organic matter content of the pond water, which could limit the efficiency of the pond water treatments.

## Output panel

The results specifying the treatment cost and the total time to treat a pond are presented in the app output panel in two dialog boxes. The treatment times were rounded to the nearest half an hour. 

When treatments are applied to increase oxygen, a plot of pond water dissolved oxygen levels for every half hour of treatment is provided to guide the user in understanding how oxygen concentration levels vary in time. In the event of ozone nanobubble treatments applied for water disinfection, the percentage of pond water treated is shown per hour of treatment.


The app is available at https://nanobubbles.shinyapps.io/nanobubble_flow/.


<p align="center">
   <img width="400" src=https://www.idrc.ca/sites/default/files/images/idrc-logo-full-name-wordmark.png>
   <br>
</p>

<p align="center">
   <img width="400" src=https://template.cityu.edu.hk/template/logo/ph/ph_logo_eng_cmyk.svg>
   <br>
</p>



<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.


 tags$a(img(height = 32, width = 35,
             src="https://img.icons8.com/?size=512&id=71474&format=png"),href="mailto:anaritamarques82@gmail.com", "Shinny app developed by Ana Marques, 2023.",style = "font-size: 1.0rem; color:#3a51b8;")
