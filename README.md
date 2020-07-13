# DDLFanAnimations
Fan art of DDL robots and their accessories in Blender

This repository contains the Blender files used to create fan animations of DDL Vector and Cozmo
robots and accessories.

Current Blender version used:  2.83.2

Current "stable" blend file (will develop better mechanism later):  ddl_cube_v6.blend

Status and caveats:
Vector's cube and all 3 Cozmo cubes modeled.
The bottom screw, text on the bottom of cube, lighting up of cubes, and cube internals have not yet been modeled.

Next is:  Cozmo's charger.

The cubes are only partially accurate to real-world size.  The cubes themselves were modeled using the default
primitive Blender cube, without using any reference image.  Thus, as you get closer into view, more inaccuracies
will become visible. The tags were created using reference images and tracing with Bezier curves.  Thus the tags are
closer to real-world, but still only as accurate as the reference images and the accuracy of the tracing.  

In other words, it's fan art :)

Specifics about .blend file:
The cubes themselves are the parent object with all of the tags.  So to move/rotate/scale, select the cube itself and not the tags.
To duplicate a cube:  Ctrl-G -> Children -> shift select cube -> Shift D -> g -> move cube
