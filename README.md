# UD_ReAgent_ABM


----------------------------------------------------------------------------------------------------------

## Installation
 - Clone this repo to get UD_VIZ ```https://github.com/VCityTeam/UD-Viz-Anthropocene-2023```
 - Place this folder at the same level of this repo to have:
  - ```YourWorkingFolder/UD_Demo_Anthropocene_2023```
  - ```YourWorkingFolder/UD-Viz-Anthropocene-2023```
  
### UD_VIZ installation 
- Install npm
- cd ```UD-Viz-Anthropocene-2023```
- ``` npm i ```
- ```npm run build ```
- Open a browser at this adress ```http://localhost:8000/debug.html```

### Demo running
- cd ```UD_Demo_Anthropocene_2023/UD-Viz-GCCV```
- ``` npm i ```
- ```npm run build ```
- ```npm run debug```
- Open a browser at this adress ```http://localhost:8000/debug.html```

## [UD-Viz](https://github.com/VCityTeam/UD-Viz) Version using a client/server architecture where UD_Viz is the client and Gama (in headless) the server



### Start your client

- ``` cd UD-Viz-GCCV ```
- (Hopefully temporal) Update your local path by editing ```FOLDER="yourpathtoUD_ReAgent_ABM"``` in the following file  ```UD-Viz-GCCV/.env```
- ``` npm i ```
- ```npm run build ```
- ```npm run start ```
- Open a browser at this adress ```http://localhost:8000/```
For Developpers you can run it in debug mpde:
- ```npm run debug```
- Open a browser at this adress ```http://localhost:8000/debug.html```

### Start the server (GAMA headless) 

- If not yet installed, download the last Gama 1.8.2 stable version [here](https://github.com/gama-platform/gama/releases/tag/1.8.2) 
- ``` cd /Applications/Gama.app/Contents/headless ``` (Mac OS) or ```cd C:\Program Files\Gama\headless``` (Windows)
- ``` bash gama-headless.sh -socket 6868 ```(Mac OS)   or ```gama-headless.bat -socket 6868``` (Windows)

----------------------------------------------------------------------------------------------------------
## [GAMA](https://gama-platform.org/) version
ABM model developped using [Gama Platform](https://gama-platform.org/). As a standalone can be used directly to be displayed on a physical table. 

- In Gama 1.8.2 Import the project ```ReAgent```
- Open ```models/Gratte_Ciel_demo.gaml```
- Run ```Demo```

----------------------------------------------------------------------------------------------------------
Agent Based Simulation framework for Urban Data Services and Vizualisation.

See the [wiki](https://github.com/VCityTeam/UD_ReAgent_ABM/wiki) for more information about this project

Contact: [Arnaud Grignard](https://github.com/agrignard) 
