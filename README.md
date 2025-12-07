# Install requirements


First Download Trackmania 2020 either through Steam, Epic games, or Ubisoft

Fair warning you will have to buy the yearly subscription for a year to be able to run any plugins like ours.

Next download OpenPlanetNext (plugins service) https://openplanet.dev/download/get?id=302


Download our zip folder and extract it.

Next you will open file explorer and go to C:/Users/Username/OpenPlanetNext/Plugins and make a folder. You will want to put the main.as and info.toml into that folder.

Go back to the OpenPlanetNext folder and open the scripts folder and make a subfolder. Place the requirements.txt cnnTorch.py and launch.bat in that folder.

Then once you open the game if you press F3 you should see a bar at the top of the game that says OpenPlanet. Next you will want to go to pluginManager and download “MLFeed: Race Data” and “MLHook: Manialink Hook & Event Inspector”.

Once those are installed you will want to run the bat script and wait until it says listening in the terminal. At this point you can click on the openplanet tab hover over signature mode and select developer mode. Lastly, you can go into a map preferably a flat map with borders and once in the game open the Plugins menu hover over GregBot and press Start Sending. Every time you rerun the code you need to stop and start the plugin as the code needs to be running before the plugin to actually connect.










## Acknowledgement

The distance estimation equations used are based on [Section 13 of Laurens Neinders' bachelor's thesis](https://essay.utwente.nl/96153/1/Neinders_BA_EEMCS.pdf)

Gaussian policy modeling and architectural inspiration in lidar-gauss.py were influenced by the [TMRL project](https://github.com/trackmania-rl/tmrl/tree/master)

Full Title: Trackmania

Release Year: 2020 (specifically July 1, 2020, for Windows)

Developer: Ubisoft Nadeo

Publisher: Ubisoft
