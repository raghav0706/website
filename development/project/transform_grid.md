---
title:
---

{% include /shared/development/warning.md %}

at the moment, people are supposed to call warp_apply, whereas elsewhere in the code transform_xxx is used (with xxx=vol/sens/headshape). It makes sense to also implement a transform_grid. Furthermore, a grid structure should be detected as such (i.e. datatype should know what a grid is).

Do we also need a griddtype function?

What is the relation between a source and a grid structure?

 
