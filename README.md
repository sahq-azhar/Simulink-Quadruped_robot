<h1 align='center'> Quadruped Robot Using MATLAB-Simulink  </h1> <br>



This repository contains the Simulink model and various supporting libraries for a Quadruped robot. This model was made for a competition and a initial simulation before planning for a prototype and building the finished robot was made to understand the various gait patterns that can be obtained using specific chassis and leg configurations. The final robot can be seen on the YouTube link provided below.

The older version of simulation will be in the 2018 folder for future reference and developments. The new improvements and optimizations will be updated in a new folder (2021).

Library Used
--------------------------------------------

<h3>Simscape Multibody Contact Forces Library</h3>

[![View Simscape Multibody Contact Forces Library on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/47417-simscape-multibody-contact-forces-library)     &nbsp;  <a href="https://github.com/mathworks/Simscape-Multibody-Contact-Forces-Library"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>

This library contains contact force models for use with Simscape Multibody. They can be used for intermittent contact (parts bouncing off each other) and persistent contact (parts resting on each other).

<h4>Important note:</h4>Since this model was created back in 2018 while installing the library make sure to install an older version to avoid any simulation and compilation errors.

current compatible library available on add-ons explorer :19.2.5.0

Media
---------------------------------------------
<img src="https://i.ibb.co/pw6SMFh/simulation.gif" alt="simulation" border="0">
<table>
  <tr>
    <td><img src="https://i.ibb.co/sJScZCh/IMG-20190206-220243.jpg" width="400" > </td>
    <td><img src="https://i.ibb.co/8NxpNBc/IMG-20190113-221416.jpg" width="400"></td>
    </tr>
     <tr>
    <td><img src="https://i.ibb.co/9Hgqt68/20190228-221925.jpg" alt="20190228-221925" border="0" width="400" > </td>
    <td><img src="https://i.ibb.co/Fx9v68R/IMG-20190202-214551.jpg" alt="IMG-20190202-214551" border="0" width="400"></td>
    </tr>
</table>

Reference
----------------------------------------------

This simulink model was created referring to 
- [MATLAB and Simulink Robotics Arena: Walking Robot](https://in.mathworks.com/matlabcentral/fileexchange/64227-matlab-and-simulink-robotics-arena-walking-robot?s_tid=srchtitle_walking%20robot_6)
- [mathworks-robotics/msra-walking-robot](https://github.com/mathworks-robotics/msra-walking-robot) 

kudos to the team for putting together such a great project.
It's all because of them that I was able to comprehend and learn from that model and create this.

Issues Resolved
--------------------------------------------------
Had a particular issue with joints going out of place was resolved later on after using revolute joint as suggested by a Matlab staff (Sebastian Castro).Thanks to him for helping.
link to the discussing (if you are intrested)
- [Facebook](https://www.facebook.com/100017607456550/videos/305468520050061/)
- [Matlab Central](https://in.mathworks.com/matlabcentral/answers/418450-i-have-followed-the-following-tutorial-but-haven-t-got-any-output-please-help-me-out?s_tid=prof_contriblnk)

Final video
--------------------------------

<a href="https://www.youtube.com/watch?v=6dfaND6Z6hM&ab_channel=TeamRoboconMJCET">
       <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
      </a>
                   


----------------------------------------------------
**⭐ The repo**



### Eat, Sleep, CODE, Repeat!





