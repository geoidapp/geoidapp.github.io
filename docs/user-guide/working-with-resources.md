---
assignees:
- adonese

---


## Resources are Automatically Modified
We built GeoidApp on a top of C/C++ libraries to take advantage of such highly optimized implementation while giving a nice front-end for the end-user to easily debug, and modify the code.

## Grid vs Point-wise

One of the design decisions we have made was to use a grid as an output instead of using point-wise mode. Our vision of surveying computations is quite big, and using a grid does meet with that vision. I think of the problem of geodesy _figure of the earth_ can be reduced even further to attract new research and professional community. I imagine it combined somehow with Google Earth to derive the height _orthometric height_ directly from Google earth.

We preserved the point-wise mode to be used in our mobile application version. We want to replace the navigator GPS with this application. We might trade the accuracy with the direct acquisition of the orthometric height. The loss is not tragic, as GPS embedded in phones are getting better over time, with a rate that is faster than the GPS navigator does.
