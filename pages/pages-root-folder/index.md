---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
callforaction:
  url: https://www.google.com/chrome/?brand=BNSD&gclid=EAIaIQobChMI9ejb1fP_9QIVo5vCCh1EWgwXEAAYASAAEgKeg_D_BwE&gclsrc=aw.ds
  text: Google Chrome browser is recommended to open this website for faster response ›
  style: terminal
permalink: /index.html

widget1:
  title: "Downloads"
  url: '/datasets/index.html'
  image: unsplash_9.jpg
  text: ''
widget2:
  title: "Acquisition System"
  url: '/getting-started/index.html'
  image: acquisition_index.png
  text: ''
widget3:
  title: "Sensors & Usage"
  url: '/sensors/index.html'
  image: sensors_page1.png
  text: ''
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

# Welcome to USTC FLICAR Dataset!
### —— USTC <font color="red">FLICAR</font>: Multisensor <font color="red">F</font>usion Dataset of <font color="red">L</font>idar-<font color="red">I</font>nertial-<font color="red">C</font>amera for Heavy-duty Autonomous <font color="red">A</font>erial Work <font color="red">R</font>obot
##### We present *USTC FLICAR Dataset*, dedicated to the development of simultaneous localization and mapping methods and precise 3D working space reconstruction for heavy-duty autonomous aerial work systems. In recent years, many public datasets have play an important roll on the progress of autonomous car and UAVs. Howerer, for the platform of aerial work robots, UAVs are not strong enough and cars can not fly. Thus, to fill in this gap, we create "Giraffe" mapping robot based on bucket truck which equipped with a variety of well calibrated and synchronized sensors: four 3D lidars, two stereo cameras, two monocular cameras, multiple Inertial Measurement Units (IMUs) and GNSS/INS system. Laser tracker is used to record the millimeter accurate position ground truth. We also made its ground twin — "Okapi" mapping robot to gather data as comparison. The main characteristic of the dataset is the application of a typical autonomous driving sensing suite to aerial scenes. Therefore, the dataset name "FLICAR" also associated with flying cars. The vision of our work is to contribute to development of flying cars, especially the take-off and landing of VTOL (Vertical Takeoff And Landing) flying cars in real environments.

## Are We Ready for Aerial Work Robots?  Or be bolder, Flying Cars?

<table>
  <tr>
    <td><img src="../../images/z_aerial_robot.png" width = "100%"></td>
  </tr>
</table>

### Some aerial work scenarios in our daily life:
<table>
  <tr>
    <td><img src="../../images/aerialwork_all.png" width = "100%"></td>
  </tr>
</table>






