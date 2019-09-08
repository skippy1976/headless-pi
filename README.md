Headless-pi is a project created to try to overcome the challenge of deploying Raspberry Pi headless systems in environments where no Raspberry Pi knowledge exists.

As an example, you may create a weather station that shows the current weather on an LED display by retrieving the information from an internet API.  To do this you would need knowledge of the local WIFI networks and ability to login to the Pi and configure this information.

Headless systems in the IoT space today to not require such complex actions, and so it is the goal of this project to create a similar mechanism that is leveraged today by many IoT devices.

The deployment of this project would consist of 2 parts:

1)  A Raspberry Pi with 
    a)  the Headless-pi project deployed and configured on it.  
    b)  an LED connected to show the user the current state.
    c)  a small switch to enable to "reset" the system.
2)  The Headless-Pi mobile application (WIPI) to configure the device
    note it is intended that this would be available from the Android and iOS app stores (not yet).
