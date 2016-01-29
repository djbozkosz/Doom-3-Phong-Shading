## Description
Modified shader (ARB_program) for Doom 3 with normal mapping and per fragment specular reflection (Phong) instead of per vertex specular reflection (Gouraud - computed as Blinn-Phong).

## Install
Paste shader file `interaction.vfp` into: `Doom 3/base/glprogs`.

## Tweak reflection
File `interaction.vfp` line `111`:
* `PARAM	consts = { 16.0, 6.0, 0.0, 0.0 };`
* first value `specular power exponent`
* second value `specular multiplier`

## Images
<div align="center">Old &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; New</div>

<img src="http://s29.postimg.org/rxyi3qvvr/d00.jpg" alt="Mars City Underground - Old" width="440">
<img src="http://s30.postimg.org/m9jz62ds1/d00.jpg" alt="Mars City Underground - New" width="440">

<img src="http://s29.postimg.org/c8nd3jeg7/d01.jpg" alt="Mars City Underground - Old" width="440">
<img src="http://s30.postimg.org/ye3u0sg1t/d01.jpg" alt="Mars City Underground - New" width="440">

<img src="http://s29.postimg.org/u6h9ytsdj/d02.jpg" alt="Mars City Underground - Old" width="440">
<img src="http://s30.postimg.org/o2mvudyyp/d02.jpg" alt="Mars City Underground - New" width="440">

<img src="http://s29.postimg.org/kn7l5d4vb/d03.jpg" alt="Mars City Underground - Old" width="440">
<img src="http://s30.postimg.org/syqim2z41/d03.jpg" alt="Mars City Underground - New" width="440">

<!--
http://s29.postimg.org/b7n4eexgn/d00.jpg
http://s29.postimg.org/isuqnmhuv/d01.jpg
http://s29.postimg.org/7pb4i0wkn/d02.jpg
http://s29.postimg.org/qwy9emew7/d03.jpg
-->
