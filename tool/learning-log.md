# Tool Learning Log

## Tool: **A-FRAME**

---

3/16/26:
* Aframe is a tool to build 3d models and VR experiences
* You can make shapes and edit their position, size, and color.
* Here's an example:
  
      a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box
      a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere
      a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder
      a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane
      a-sky color="#ECECEC"></a-sky>
  
    this simple code adds some simple colored 3d shapes to a scene.

### 3/29/26:
* Positioning is something you use to dictate where the object is. It is measured in 3 dimensional X, Y, and Z values.
* Relative positioning is the position of an object based on the position of a different, preexisting parent object.
  
``<a-box position="-1 0.5 -5" rotation="0 45 0" color="#689F38" width="0.5"><a-circle position="0 0 1"></a-circle></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E" height="2"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="1" segments-radial="6" height="1.5" color="#FFC65D" ></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>``
      
Example code for  positioning and relative positioning.
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

### 4/20/26
WED
* Learned about rotation and relative rotation.
* Rotation uses the right hand rule, and degrees to measure.
  Here is some example code messing around with rotation and relative rotation.
  
  ``<a-box position="-1 0.5 -5" rotation="90 45 0" color="#689F38" width="0.5"><a-circle position="0 0 1" rotation="-90 0 0"></a-circle></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E" height="2"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="1" segments-radial="6" height="1.5" color="#FFC65D" ></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>``

THU
* Learned about scale and relative scale
* Scale simply effecets the object's size. Relative scale changes size based on a parent object.
  Here us some example code with scale and relative scale.

  ``<a-box position="-1 0.5 -5" rotation="90 45 0" color="#689F38" width="0.5" scale="3 3 3"><a-circle position="0 0 1" rotation="-90 0 0" scale="2 1 1"></a-circle></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E" height="2" scale="1 1 1"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="1" segments-radial="6" height="1.5" color="#FFC65D" ></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>``
FRI
* Made a simple multi object structure.
  Here's the simple structure based on what ive learned

``  <a-box position="0 0 0" rotation="90 45 0" color="#964B00" width="1" scale="1 1 5">
      <a-sphere position="0 0 -0.5" color="#006400" scale="2 2 0.5"></a-sphere>
      <a-sky color="#ECECEC"></a-sky>``

