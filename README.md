# NEST style thermostat with temperature week scheduler
Dashboard widget for Node-RED - Hass.io Ready

## Original projects
This project is an integration of these:
* [NEST style thermostat Dashboard widget for Node-red](https://github.com/automatikas/Node-red-Nest-thermostat)
* [A Thermostat Weekend](https://tech.scargill.net/tag/a-node-red-dashboard-thermostat-in-the-making/)
* [Temperature/ON-OFF Week Scheduler UI-Template Node-Red Dashboard](https://flows.nodered.org/flow/65f411e9e37745a4bbeef5926d052c97)

## Screenshots
### Off:
![Screenshot image_01](images/Nest_off.PNG)

### On:
![Screenshot image_02](images/Nest_on.PNG)

### Heat:
![Screenshot image_03](images/Nest_heat.PNG)

### Away:
![Screenshot image_04](images/Nest_away.PNG)

### Scheduler:
![Screenshot image_05](images/Scheduler.PNG)

## How to install
Download the file flow.json, then go to your node-red application and press **`import`** > **`cliboard`** and finally select the file saved.

## How to use
Modify the following nodes configuring the data source (ex: Home Assistant server):
* Climate
* Away from Alarm
* svc: climate:set_temperature
* svc: climate:turn_off
* svc: climate:turn_on

## Features
* Thermostat status: OFF, ON with target temperature, Heat, Away mode (limits the maximum temperature) 
* Thermostat control: Off or On by scheduler
* Week Scheduler

## TODO
* Manual and countdown modes
* Improve the graphics component (currently: only horizontal and with problems in resizing)
