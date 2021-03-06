# Balancing climate change and digital growth

## Datacenter energy growth

![energy-forecast](images/energy-forcast.png)
source: https://www.nature.com/articles/d41586-018-06610-y

## Energy = C02 emissions

Example:  In Australia, 618g CO2 per kWh, For 1 server 100W =  541Kg C02/year

Carbon intensity of electricity consumed (gCO₂eq/kWh)
![elactrical-map](images/electrical-map.png)
source https://app.electricitymap.org/map 


## Datacenter Power Usage Effectiveness (PUE)

The average power usage effectiveness (PUE) ratio for a data center in 2020 is 1.58, only marginally better than 7 years ago, according to the latest annual Uptime Institute survey (findings to be published shortly).

![datacenter-pu](images/datacenter-pu.png)
source: https://www.mitsubishicritical.com/resources/improve-power-usage-effectiveness/

1 Server = 514 * 1.58 = 855 Kg C02/year

A tree absorbe about 28 Kg/year in average, so 1 server is compensated by 30 trees.

## Solar Floating PV Plants

* 15 years experience
* 240 installed projects
* 600+ MWp
* 30 countries (including USA)
* Patented technology from [Ciel-et-Terre](https://www.ciel-et-terre.net/)

![main](images/ciel-et-terre1.png)
![hydrelio](images/ciel-et-terre2.png)

## Innovation : Solar Floating PV Datacenters

Add underwater servers powered directly by PV panels:
* Underwater aluminium waterproof boxes including a motherboard and SSD disks
* Efficient cooling in a dielectric fluid using the passive thermosyphon effect.
* A Switched BMS battery to store and convert PV panel energy

![hydrobax](images/hydropbox.png)

## Underwater view : immersed battery + server

![underwater-view](images/underwater-view.png)

## Helicopter view : autonomous repeatable cells

![underwater-view](images/helicopter-view.png)

## Satellite view : small distributed kubernetes clusters

![satellite-view](images/satellite-view.png)

## Switched BMS Battery

The switched Battery Management System dynamically configure 1.2v cells in serie and parallel to accept and deliver any kind of voltages. (Patented technology from [otonohm](https://www.otonohm.com/our-technology))

![bms-battery](images/bms-battery.png)

Solar monitoring and prediction help to size and manage enargy storage.

![solar-monitoring](images/solar-monitoring.png)

## Benefits : Datacenter PUE ~= 0

* No more high-low voltage conversion and transport loss, short and thick electrical cables.
* No more energy for cooling, the dielectric fluid and the water spread the heat (and the PV panels block solar heat input), the thermosyphon effect helps to spread the heat for free.
* Cheaper servers with no more power supply and fans, longer lifetime because there is no more vibration and air oxidation (see benefits on [grcooling](https://www.grcooling.com/electrosafe-dielectric-liquid-coolant/) )
* No need for a building, a humidity control system, and fire suppression system.
* The kubernetes pod placement helps to manage failures or lack of energy. 
	* Batch and test workloads running during daily hours requires smaller batteries.
	* AstraDB/Cassandra/Elassandra and Apache Pulsar may help in moving transparently running applications and hot data from a k8s cluster to another.




