# Simulating the spread of the forest fire in CAPyLE

Added new cellular automata description for `forest_fire_spread.py` that simulates spread of forest fire caused by incinerator or/and powerplant.

<div display="flex" flex-direction="row" >
<img src="https://github.com/Anastasiia66/bioinspired_ca_forest_fire_spread/blob/main/Gif1_north_prevailing%20.gif" width="300" height="300"/>
</div>

Simulation of the fire spreading on a 2D grid with the prevailing north wind effect. (Wind direction set to North and wind velocity set to 1)

Our model defines terrain types with different propabilities of catching a fire and different burn times.

- Dense forest (dark green colour), difficult to ignite but can burn for up to one month (30 days = 180 generations). 
- Chaparral (light green colour), catches fire quite easily, can burn for a period of several days (7 days = 42 generations).
- Canyon (yellow colour), very easy to catch fire, but burns for only several hours (12 hours = 3 generations).
- Lake (blue colour), can't be ignited.
- Fire break (brown colour), can't be ignited.

## Instructions to run the forest_fire_spread
### How to set the wind direction and velocity



Our model takes into acount wind direction and velocity affecting spread of fire. The model can also simulate short intervention of dropping 12.5 km^2 of water in different intervention times and different areas. 

Once the fire reaches the town, simulation reports results in the command promt. 



# CAPyLE
CAPyLE is a cross-platform teaching tool designed and built as part of a final year computer science project. It aims to aid the teaching of cellular automata and how they can be used to model natural systems.

It is written completely in python with minimal dependencies.

![CAPyLE Screenshot on macOS](http://pjworsley.github.io/capyle/sample.png)

## Installation
The installation guide can be found on the [CAPyLE webpages](http://pjworsley.github.io/capyle/installationguide.html)

## Usage
Detailed usage can be found on the [CAPyLE webpages](http://pjworsley.github.io/capyle/).

See below for a quickstart guide:

1. `git clone https://github.com/pjworsley/capyle.git [target-directory]`
2. `cd [target-directory]`
3. Execute main.py either by:
    * `run.bat` / `run.sh`
    * `python main.py`
2. Use the menu bar to select File -> Open. This will open in the folder `./ca_descriptions`.
3. Open one of the example files;
  - `wolframs_1d.py` is Wolfram's elementary 1D automata
  - `gol_2d.py` is Conway's 2D game of life
4. The main GUI elements will now load, feel free to customise the CA parameters on the left hand panel
5. Run the CA with your parameters by clicking the bottom left button 'Apply configuration & run CA'
6. The progress bar will appear as the CA is run
7. After the CA has been run, use the playback controls at the top and the slider at the bottom to run through the simulation.
8. You may save an image of the currently displayed output using the 'Take screenshot' button

## Acknowledgements
Special thanks to [Dr Dawn Walker](http://staffwww.dcs.shef.ac.uk/people/D.Walker/) for proposing and supervising this project.

Also thanks to the COM2005 2016/2017 cohort for being the guinea-pigs!

## Licence
CAPyLE is licensed under a BSD licence, the terms of which can be found in the LICENCE file.

Copyright 2017 Peter Worsley
