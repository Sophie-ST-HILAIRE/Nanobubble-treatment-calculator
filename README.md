# Nanobubble treatment calculator

Welcome to the [Nanobubble Treatment Calculator](https://nanobubbles.shinyapps.io/nanobubble_flow/), an online app to determine nanobubble treatments time and costs for your aquaculture pond. Select from the available options: 
1. To increase pond water oxygen levels, by applying oxygen nanobubble treatments, or 
2. To reduce algae and bacteria through the application of ozone nanobubbles. 

The app calculates cost and treatment time for one pond and one treatment event. User specified input is entered in the input panel, where default values are initially provided, while treatment cost and treatment time outputs are provided in the app output section.
<p align="center">
<img width="400" src=https://github.com/Sophie-ST-HILAIRE/Nanobubble-treatment-calculator/blob/main/Nanobubble_treatmet_App.png/>
   <br>
    <em> Fig. 1: Nanobuble treatment app input panel for treatment specifications, and corresponding outputs.</em>
</p>

## Input panel

After selecting the purpose of the nanobubble treatment, the user is asked to specify if the energy to power the nanobubbler is supplied via the electric grid or using a rented diesel powered generator. In the event of the electricity supplied from the grid, the price of electricity per kwh can be customized in the "Customization" section of the user input panel. If the option "Generator (diesel)" is selected, the user can specify if they are renting the generator and the rental cost per hour; diesel generator efficiency (%), the cost of fuel per liter, and the fuel energy content can be customized in the "Customization" section of the user input panel. The default values are set to USD but any value can be set by the user.

Nanobubblers are often coupled to ozone or oxygen generator. Three options are provided to select nanobubblers associated to ozone or oxygen generators in the input parameter "Select the equipment used". These three options automatically provide the calculator with the water and electricity consumption parameters for each of the three setups. Furthermore, the user can select a fourth option in the list of equipment to customize the specifications of the nanobubbler, with or without the addition of a gas generator, in the "Customization" section. Here, the energy consumption per hour for the nanobubbler or nanobubbler and generator setup, can be specified, along with the oxygen output and equipment water flow. The number of nanobubblers, or nanobubble and generator setups, can be specified in an additional input "How many machines will you use to treat one pond?". The user should also specify the pond volume in cubic meters, where one cubic meter is the equivalent to 1000 L.

## Output panel

The results specifying the treatment cost and the total time to treat a pond are presented in the app output panel in two dialog boxes. The treatment times were rounded to the nearest half an hour. 

When treatments are applied to increase oxygen, a plot of pond water dissolved oxygen levels for every half hour of treatment is provided to guide the user in understanding how oxygen concentration levels vary in time. In the event of ozone nanobubble treatments applied for water disinfection, the percentage of pond water treated is shown per hour of treatment. 

The app provides estimates of treatment times and should be used to guide the nanobubbler users, who should expect variations due to organic matter content, pond water temperature, nanobubble distribution efficiency in the pond, variations in sunlight and algae, among other parameters influencing treatment results. Additionally, nanobubbler users are encouraged to verify that their equipment is functioning properly by measuring the dissolved oxygen or ozone content of the output water, which can potentially vary during the treatment and influence treatment efficacy.

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


App developed by [Ana Marques](mailto:anaritamarques82@gmail.com?subject=[GitHub]%20Source%20Han%20Sans), 2023. This app repository is also maintained by [Ana Marques](mailto:anaritamarques82@gmail.com?subject=[GitHub]%20Source%20Han%20Sans).
