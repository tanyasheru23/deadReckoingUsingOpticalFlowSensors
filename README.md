# Dead-Reckoning-for-optical-based-sensors

<br>
In order to develop an accurate localization system for robots, we have implemented a dead reckoning system that relies on measuring the incremental movements of the robot directly from the floor using optical mouse sensors. These sensors allow us to measure the movement along two axes. To accurately calculate the robot's position and orientation deviation, it is essential to attach two optical mouse sensors to the robot. By analyzing the sensor values obtained from these sensors, we have conducted several experiments with the prototype to validate the effectiveness of the algorithm used in the system.
<br>
<br>
Dead reckoning is a method used to determine one's position by utilizing a
previously established position and considering the distance and direction traveled since
that position was last determined. Dead reckoning systems find extensive application in
navigation systems. For instance, they are employed when the GNSS system of a satellite
is nonfunctional. Many automated robots also rely on dead reckoning to ascertain their
positions, such as room cleaning and grass cutting robots. However, employing
high-quality sensors increases the cost of the product, and some products have
limitations, such as functioning exclusively on smooth and horizontal surfaces.
Therefore, our project aims to develop a cost-effective dead reckoning system capable of
operating on even surfaces using two high-DPI optical mouse sensors and a Raspberry Pi.
We have selected 10,000 DPI mouse sensors, which are ideal for tracking small
movements, while the Raspberry Pi provides a robust and flexible platform for data
processing and analysis.
The project involved the design and construction of a prototype system, which
will include two gaming mice, a Raspberry Pi, DC motors, motor drivers, and other
necessary components. The system did undergo calibration and testing using a ground
truth reference system, such as a motion capturing system, to assess its accuracy and
performance. This system holds potential for various applications, particularly in the field
of robotics, where precise tracking of a robot's position is essential for effective
navigation and obstacle avoidance. For instance, it can be implemented in self-cleaning
robots that require knowledge of their position to thoroughly clean every corner of a
room, as well as in tasks involving navigation and obstacle avoidance.

<b>References</b>
<ol>
  <li>https://www.researchgate.net/publication/221645389_Dead_Reckoning_for_Mobile_Robots_Using_Two_Optical_Mice?enrichId=rgreq-3843766b9040efe08de2bd72c4f78e48-XXX&enrichSource=Y292ZXJQYWdlOzIyMTY0NTM4OTtBUzoxMDIwNjMyMDc4Nzg2NTdAMTQwMTM0NTE3MzA3MQ%3D%3D&el=1_x_2&_esc=publicationCoverPdf</li>
  <li>https://python-evdev.readthedocs.io/en/latest/</li>
  <li>https://numpy.org/doc/</li>
  <li>https://www.raspberrypi.org/</li>
  <li>https://socket.io/</li>
</ol>

