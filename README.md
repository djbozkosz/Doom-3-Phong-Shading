## Description
Modified shader (ARB_program) for Doom 3 with normal mapping and per fragment specular reflection (Phong) instead of per vertex specular reflection (Gouraud - computed as Blinn-Phong).

## Install
Paste shader file `interaction.vfp` into: `Doom 3/base/glprogs`.

## Tweak reflection
File `interaction.vfp` line `111`:
* `PARAM	consts = { 8.0, 6.0, 0.0, 0.0 };`
* first value `specular power exponent`
* second value `specular multiplier`

## Images
<div align="center">Old &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; New</div>

<img src="https://s29.postimg.cc/rxyi3qvvr/d00.jpg" alt="Mars City Underground - Old" width="440">
<img src="https://s30.postimg.cc/m9jz62ds1/d00.jpg" alt="Mars City Underground - New" width="440">

<img src="https://s29.postimg.cc/c8nd3jeg7/d01.jpg" alt="Mars City Underground - Old" width="440">
<img src="https://s30.postimg.cc/ye3u0sg1t/d01.jpg" alt="Mars City Underground - New" width="440">

<img src="https://s29.postimg.cc/u6h9ytsdj/d02.jpg" alt="Mars City Underground - Old" width="440">
<img src="https://s30.postimg.cc/o2mvudyyp/d02.jpg" alt="Mars City Underground - New" width="440">

<img src="https://s29.postimg.cc/kn7l5d4vb/d03.jpg" alt="Mars City Underground - Old" width="440">
<img src="https://s30.postimg.cc/syqim2z41/d03.jpg" alt="Mars City Underground - New" width="440">

<!--
https://s29.postimg.cc/b7n4eexgn/d00.jpg
https://s29.postimg.cc/isuqnmhuv/d01.jpg
https://s29.postimg.cc/7pb4i0wkn/d02.jpg
https://s29.postimg.cc/qwy9emew7/d03.jpg
-->
