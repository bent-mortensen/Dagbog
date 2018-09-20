# Connectivity Issues

|Device       |            |
|-------------|------------|
|Name         |ka-iot-win10|
|OS           |10.0.17134.1|

This device is meant to be powered on 24/7.  
So far the device have only been connected to the k|a Guest network over wifi, if the connectivity issue is related to this setup, 
then we need to test on a IRL situation, with a static ip address on a generic wifi router or a wired connection.

## Observations

The device will occasional lose connection, between tests.  
The device will occasional BSOD on bootup.  
The device will often lose connection, to the wifi network, over night.  
The device will often lose connection, to the wifi network, when the house is busy. Days with full parkinglot or Fridays typical.  

## Implication

The over all implication is loss of productivity!

### if (connectionLost == true)  
{  
* Time spent figuring out what is worng
* Time spent fixing the problem
* Time spent getting back on track
* Time spent interrupting the team
* Time spent not actual working on writing code/debugging

}  

If the connection is lost, we need a reliable way to reestablish the connection. So far a hard reset (Cut power) has been the best way,
getting the device to reconnect. A solution which is not an option, when the device is deployed.

### if (BSOD == true)  
{  
* Time spent on hard reboot (Cut power)
* Time spent on location SD card reader
* Time spent on installing new FFU
* Time spent on setup of newly createt win10iot
* Time spent on connecting to wifi again

}  
