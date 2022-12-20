# ECG-BASED-HEART-RATE-MONITORING-SYSTEM-USING-ARDUINO
<p>I have built a low-cost ECG-based heart rate monitoring system using Arduino to measure a person's heart rate in real-time or record for later study. 
Built an affordable device costing around 15 USD to help patients get diagnosed from the comfort of their homes without traveling to the hospital.</p>

<h2><b>The Heartbeat Sensor</b></h2>

<p align="justify">Heartbeat Sensor is an electronic device that is used to measure the heart rate i.e. speed of the heartbeat. Monitoring body temperature, heart rate and blood pressure are the basic things that we do in order to keep us healthy. Heart Rate can be monitored in two ways: one way is to manually check the pulse either at wrists or neck and the other way is to use a Heartbeat Sensor</p>
<p align="justify">The principle behind the working of the Heartbeat Sensor is Photoplethysmograph. According to this principle, the changes in the volume of blood in an organ is measured by the changes in the intensity of the light passing through that organ.</p>

<h2>Working of Heartbeast Sensor</h2>
<p align="justify">A simple Heartbeat Sensor consists of a sensor and a control circuit. The sensor part of the Heartbeat Sensor consists of an IR LED and a Photo Diode placed in a clip. The sensor has a clip to insert the finger and has three pins coming out of it for connecting VCC, GND and the Data.</p>

<h2>Pin Wiring</h2>
Wiring your sensor to the Arduino is pretty simple:<br></br>
<table>
  <tr>
    <td>Pin</td>
    <td>Wiring to Arduino Uno</td>
  </tr>
    <td>A0</td>
    <td>Analog Pins</td>
  </tr>
    <td>GND</td>
    <td>GND</td>
  </tr>
  <td>VCC</td>
    <td>5V</td>
  </tr>
</table>
<div>
<h2>Instructions to run the code:</h2>
<p align="justify">
1] Upload the code in arduino.cc file to your arduino board<br></br> 
2] After uploading the code open serial monitor at 115200 baud rate, and put your fingure at the heartbeat sensor module. you will see your heartbeat in BPM.
</p>
<p align="justify">*For adults 18 and older, a normal resting heart rate is between 60 and 100 beats per minute (bpm), depending on the person’s physical condition and age. For children ages 6 to 15, the normal resting heart rate is between 70 and 100 bpm, according to the AHA.</p>
</div>
<h2>Hardware Screenshot</h2>
<img src="https://user-images.githubusercontent.com/48044041/208750325-7e5990c5-ec3d-4bb9-bf60-9c7d63b8e65c.png" width="60%" height="60%">
<h2>Output Screenshot:</h2>
<img src="https://user-images.githubusercontent.com/48044041/208750224-86ce16d7-575c-44ed-b898-c3517e89072e.png" width="60%" height="60%">
