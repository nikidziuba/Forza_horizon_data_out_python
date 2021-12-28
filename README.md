# This is a simple python UDP server for reading telemetry data from Forza Horizon 4 and 5

### What you need: 
- One of the FH games
- A Raspberry Pi or other device that can run a Python server
- sockets module for, well, socket server and struct module for unpacking data 

This script is using the Data Out feature of Forza games which you can read about [here](https://forums.forzamotorsport.net/turn10_postst128499_Forza-Motorsport-7--Data-Out--feature-details.aspx), on official Forza Motorsport forum

#### To turn on Data Out, go to hud options and configure following parameters:
- #### Data Out: Toggles the data output function on and off.
- #### Data Out IP Address: The target IP address of the remote machine receiving data.
- #### Data Out IP Port: The target IP port of the remote machine receiving data, which you can set in the python script

Data is saved in a dictionary (returned_data) that you can freely use
Data format is available in data_format.txt or on the forum 