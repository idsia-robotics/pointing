# Pointing

## Publications

### Interacting with a Conveyor Belt in Virtual Reality using Pointing Gestures

Jérôme Guzzi, Gabriele Abbate, Antonio Paolillo and Alessandro Giusti
_HRI2022 Demo, to appear_

<details>
  <summary>Abstract</summary>
  We present an interactive demonstration where users are immersed in a virtual reality simulation of a logistic automation system. Using pointing gestures sensed by wrist-worn inertial measurement unit, users select defective packages transported on conveyor belts. The demonstration allows users to experience a novel way to interact with automation systems, and shows an effective application of virtual reality for human-robot interaction studies.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/guzzi2022demo.pdf"| relative_url }})

<div class="video-container">
        <video width="100%" controls>
          <source src="files/videos/guzzi2022demo.mp4" type="video/mp4" />
        </video>
</div>

---

### PointIt: A ROS Toolkit for Interacting with Co-located Robots using Pointing Gestures

Gabriele Abbate, Alessandro Giusti, Antonio Paolillo, Boris Gromov, Luca Gambardella, Andrea Emilio Rizzoli and Jérôme Guzzi
_HRI2022 Short Contribution, to appear_

<details>
  <summary>Abstract</summary>
  We introduce PointIt, a toolkit for the Robot Operating System (ROS2) to build human-robot interfaces based on pointing gestures sensed by a wrist-worn Inertial Measurement Unit, such as a smartwatch.  We release the software as open-source with MIT license; docker images and exhaustive instructions simplify its usage in simulated and real-world deployments.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/abbate2022short.pdf"| relative_url }})

[Details](https://github.com/Gabry993/pointing-user-interface-hri)

---

### IMU-based pointing for package selection on industrial conveyor belts

Gabriele Abbate, Alessandro Giusti, Antonio Paolillo, Luca Maria Gambardella, Andrea Emilio Rizzoli and Jérôme Guzzi

<details>
  <summary>Abstract</summary>
We introduce an intuitive pointing-based interface to select objects moving on a system of conveyor belts. The interface has minimal sensing requirements, as the operator only needs to wear an Inertial Measurement Unit on the wrist (e.g., a smartwatch). LED strips provide the required visual feedback to precisely point to the objects and select them. We experimentally compare the proposed approach with a baseline mouse-based graphical user interface in which the user can click on packages with a mouse. Quantitative results show that our interface compares favorably to the baseline, especially in difficult scenarios involving many packages moving fast.
</details>

[Details](https://github.com/idsia-robotics/pointing-belts)


<iframe width="560" height="315" src="https://www.youtube.com/embed/hB33cX6pvmg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/3J1HDkwa8qU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

---

### Pointing at Moving Robots: Detecting Events from Wrist IMU Data

Gabriele Abbate, Boris Gromov, Luca M. Gambardella, and Alessandro Giusti.
_in 2021 IEEE International Conference on Robotics and Automation (ICRA), pp. 3604-3611, 2021_

<details>
  <summary>Abstract</summary>
 We propose a practical approach for detecting the event that a human wearing an IMU-equipped bracelet points at a moving robot; the approach uses a learned classifier to verify if the robot motion (as measured by its odometry) matches the wrist motion, and does not require that the relative pose of the operator and robot is known in advance. To train the model and validate the system, we collect datasets containing hundreds of real-world pointing events. Extensive experiments quantify the performance of the classifiers and relevant metrics of the resulting detectors; the approach is implemented in a real-world demonstrator that allows users to land quadrotors by pointing at them.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/abbate2021moving.pdf"| relative_url }})

<iframe width="560" height="315" src="https://www.youtube.com/embed/x7Xt7Xr7pWk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


---

### Intuitive 3D Control of a Quadrotor in User Proximity with Pointing Gestures

B. Gromov, J. Guzzi, L. Gambardella, and A. Giusti
_in 2020 IEEE International Conference on Robotics and Automation (ICRA), 2020, pp. 5964-5971_

<details>
  <summary>Abstract</summary>
 We present an approach for controlling the position of a quadrotor in 3D space using pointing gestures; the task
is difficult because it is in general ambiguous to infer where,
along the pointing ray, the robot should go. We propose and
validate a pragmatic solution based on a push button acting as a
simple additional input device which switches between different
virtual workspace surfaces. Results of a study involving ten
subjects show that the approach performs well on a challenging
3D piloting task, where it compares favorably with joystick
control.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/gromov2020intuitive.pdf"| relative_url }})


<iframe width="560" height="315" src="https://www.youtube.com/embed/9PeCe9AVh-4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[Details](/3d-pointing/index.html)

---

### Guiding Quadrotor Landing with Pointing Gestures

B. Gromov, L. Gambardella, and A. Giusti
_in Human-Friendly Robotics 2019, Cham, 2020, pp. 1–14_

<details>
  <summary>Abstract</summary>
 We present a system which allows an operator to land a
quadrotor on a precise spot in its proximity by only using pointing gestures; the system has very limited requirements in terms of robot capabilities, relies on an unobtrusive bracelet-like device worn by the operator,
and depends on proven, field-ready technologies. During the interaction,
the robot continuously provides feedback by controlling its position in
real time: such feedback has a fundamental role in mitigating sensing inaccuracies and improving user experience. We report a user study where
our approach compares well with a standard joystick-based controller in
terms of intuitiveness (amount of training required), landing spot accuracy, and efficiency
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/gromov2020guiding.pdf"| relative_url }})

---

### Proximity Human-Robot Interaction Using Pointing Gestures and a Wrist-mounted IMU

B. Gromov, G. Abbate, L. Gambardella, and A. Giusti
_in 2019 IEEE International Conference on Robotics and Automation (ICRA), 2019, pp. 8084–8091_

<details>
  <summary>Abstract</summary>
 We present a system for interaction between colocated humans and mobile robots, which uses pointing gestures
sensed by a wrist-mounted IMU. The operator begins by
pointing, for a short time, at a moving robot. The system
thus simultaneously determines: that the operator wants to
interact; the robot they want to interact with; and the relative
pose among the two. Then, the system can reconstruct pointed
locations in the robot’s own reference frame, and provide
real-time feedback about them so that the user can adapt
to misalignments. We discuss the challenges to be solved to
implement such a system and propose practical solutions,
including variants for fast flying robots and slow ground robots.
We report different experiments with real robots and untrained
users, validating the individual components and the system as
a whole.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/gromov2019proximity.pdf"| relative_url }})

<iframe width="560" height="315" src="https://www.youtube.com/embed/hyh_5A4RXZY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<!-- ### Video: Pointing Gestures for Proximity Interaction

B. Gromov, J. Guzzi, G. Abbate, L. Gambardella, and A. Giusti
_in HRI ’19: 2019 ACM/IEEE International Conference on Human-Robot Interaction, March 11–14, 2019, Daegu, Rep. of Korea, 2019_
<details>
  <summary>Abstract</summary>
</details>
https://youtu.be/yafy-HZMk_U -->
[Details](/pointing-gestures/index.html)

---

### Demo: Pointing Gestures for Proximity Interaction

B. Gromov, J. Guzzi, L. Gambardella, and A. Giusti
_in HRI ’19: 2019 ACM/IEEE International Conference on Human-Robot Interaction, March 11–14, 2019, Daegu, Rep. of Korea, 2019_
<details>
  <summary>Abstract</summary>
 We demonstrate a system to control robots in the users proximity with pointing gestures-a natural device that people use all the time to communicate with each other. Our setup consists of a miniature quadrotor Crazyflie 2.0, a wearable inertial measurement unit MetaWearR+ mounted on the user's wrist, and a laptop as the ground control station.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/gromov2019demo.pdf"| relative_url }})

<!-- award img/gromov2019demo-award.jpg -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/yafy-HZMk_U" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

---

### Robot Identification and Localization with Pointing Gestures

B. Gromov, L. Gambardella, and A. Giusti
_in 2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2018, pp. 3921–3928_

<details>
  <summary>Abstract</summary>
 We propose a novel approach to establish the
relative pose of a mobile robot with respect to an operator that
wants to interact with it; we focus on scenarios in which the
robot is in the same environment as the operator, and is visible
to them. The approach is based on comparing the trajectory of
the robot, which is known in the robot’s odometry frame, to the
motion of the arm of the operator, who, for a short time, keeps
pointing at the robot they want to interact with. In multi-robot
scenarios, the same approach can be used to simultaneously
identify which robot the operator wants to interact with. The
main advantage over alternatives is that our system only relies
on the robot’s odometry, on a wearable inertial measurement
unit (IMU), and, crucially, on the operator’s own perception.
We experimentally show the feasibility of our approach using
real-world robots.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/gromov2018robot.pdf"| relative_url }})

<iframe width="560" height="315" src="https://www.youtube.com/embed/VaQ3aZBf_uE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[Details](/motion-relloc/index.html)

---

### Video: Landing a Drone with Pointing Gestures

B. Gromov, L. Gambardella, and A. Giusti
_in HRI ’18 Companion: 2018 ACM/IEEE International Conference on Human-Robot Interaction Companion, March 5–8, 2018, Chicago, IL, USA, 2018_

<details>
  <summary>Abstract</summary>
 We demonstrate an intuitive gesture-based interface for manually
guiding a drone to land on a precise spot. Using unobtrusive wearable sensors, an operator can quickly and accurately maneuver and
land the drone after very little training; a preliminary user study
on 5 subjects shows that the system compares favorably with a
traditional joystick interface.
</details>


[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/gromov2018video.pdf"| relative_url }})

<iframe width="560" height="315" src="https://www.youtube.com/embed/jpG8Jsmth2Y" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[Details](/hri-landing/index.html)

---

### Learning to detect pointing gestures from wearable IMUs

D. Broggini, B. Gromov, L. M. Gambardella, and A. Giusti
_in Proceedings of Thirty-Second AAAI Conference on Artificial Intelligence, February 2-7, 2018, New Orleans, Louisiana, USA, 2018_

<details>
  <summary>Abstract</summary>
 We propose a learning-based system for detecting when a
user performs a pointing gesture, using data acquired from
IMU sensors, by means of a 1D convolutional neural network.
We quantitatively evaluate the resulting detection accuracy,
and discuss an application to a human-robot interaction task
where pointing gestures are used to guide a quadrotor landing
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/broggini2018learning.pdf"| relative_url }})

---

### Wearable multi-modal interface for human multi-robot interaction

 B. Gromov, L. M. Gambardella, and G. A. Di Caro
 _in Safety, Security, and Rescue Robotics (SSRR), 2016 IEEE International Symposium on, 2016, pp. 240–245_
<details>
  <summary>Abstract</summary>
  A complete prototype for multi-modal interaction
between humans and multi-robot systems is described. The
application focus is on search and rescue missions. From the
human-side, speech and arm and hand gestures are combined
to select, localize, and communicate task requests and spatial
information to one or more robots in the field. From the robot
side, LEDs and vocal messages are used to provide feedback
to the human. The robots also employ coordinated autonomy
to implement group behaviors for mixed initiative interaction.
The system has been tested with different robotic platforms
based on a number of different useful interaction patterns.
</details>

[![PDF]({{ "/files/img/pdf1.png" | relative_url }} "Download Paper")]({{"/files/gromov2016wearable.pdf"| relative_url }})

<iframe width="560" height="315" src="https://www.youtube.com/embed/FWMCxARQYhY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

