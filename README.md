# KUKA-UI
An open-source software interface for integration of Kuka robot manipulators with peripheral tools and sensors. The software is developed based on Kuka Fast Research Interface (FRI) which enables real-time control of the robot. Simulink Desktop Real-Time or any User Datagram Protocol (UDP) client can send real-time commands to Kuka robot. Third-party tools can be added and controlled synchronously with Kuka Light-Weight Robot (LWR). The control commands can be sent via serial communication to the attached tool. Low-level commands are also possible to be generated by Data Acquisition (DAQ) board. This feature enables the rapid prototyping of new devices to be used alongside the Kuka manipulator. Type II Reflexxes Motion Library is used to generate an online trajectory for Kuka LWR and the attached device in different control modes. A wide range of sensors such as strain gauges, compression load cells, pressure sensors/barometers, piezoresistive accelerometers, magnetoresistive sensors (compasses) can be interfaced not only by a DAQ board but also through the connection interface of amplified bridges. Furthermore, sensors data, as well as all robot parameters such as joint variables, Jacobian matrix, mass matrix, etc. can be logged during the experiments in a separate stable thread. All these capabilities are readily available through a multithreaded Graphical User Interface (GUI).
# Dependencies
To compile the code, you need the following libraries:
- FRI_Remote
- TypeIIRML
- NI-DAQmx
- Phidgets21 Libraries
# Wiki
- Get started here:
https://github.com/mahyaret/KUI/wiki/Get-Started
- Check the Wiki page for understanding functions details:
https://github.com/mahyaret/KUI/wiki
# News and Updates
http://www.etedal.net/p/kuka.html
# YouTube
- Watch this short video to see how the program works: 
https://youtu.be/2uZ6xMaOPbs
- Watch this short video to see some of the features of the program:
https://youtu.be/vEYGTlQS7Z0
