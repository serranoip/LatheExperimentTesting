# LatheExperimentTesting
 
## **Prerequisites**
* MATLAB R2023a (this app hasn't been tested with other MATLAB versions)
* Data Acquisition Toolbox
* Data Acquisition Toolbox Support Package for National Instrument NI-DAQmx Devices

## **Hardware Setup**
### **Arduino**
* Plug in the arduino and follow the picture below
![image info](/pictures/arduino.png)

### **Circuit**
* Once the Arduino power has been connected, follow the schematic below
![image info](/pictures/circuit.PNG)

* To double check if you have done the correct wiring, here's a reference picture of the breadboard with connections
![image info](/pictures/reference.png)

* DAQ wiring picture
![image info](/pictures/daq.png)

## **Software Setup**
* Download the folder (Lathe App) in this repo
* Open the folder the *LiveDataAcquisition.mlapp*
* Once finished, the GUI should open.
* If everything's ready, follow the settings below:
![image info](/pictures/settings.PNG)

* Once your settings matched, press **START** and the app should start

## **Potential Solutions if the system is not working**
* Check wiring; the leads of the wires might be cut off and not connected to either the DAQ or the breadboard
* Restart the MATLAB app

## **Final Test Result - 05/17**
![image info](/pictures/test.PNG)