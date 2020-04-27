# MultiView Video Capture with Zoom

DIY Computer Vision at Home  -  multiple view video capture using Zoom


Using [Zoom](https://zoom.us/) software for videotelephony, a meeting can be accessed with multiple devices 
and the session can be recorded by the host device (screen capture). When a single participant connect with multiple devices in the online zoom meeting, the recording of the meeting provides one video (mp4, 1280 x 720 at 25fps) with  multiple view capture of the participant. 
A downsample example is shown below: the recording was done using 4 devices attending the same zoom meeting:  
- PC (windows 10, wired broadband, host recording the meeting) 
- 3 wireless devices (ipad + android smartphone + windows laptop).  

The multiple views appearing in the Zoom video are  all well synchronised overall.

<img width="200" alt="multiple video video capture" src="ZoomImageppt.png">
 
Multiple view videos have historically many applications in computer video 
(e.g. for performance capture for 3D rendering) and combined with sound, provides suitable recordings for [Audio Visual Speech Recognition research](https://en.wikipedia.org/wiki/Audio-visual_speech_recognition), and this approach (using recording of meeting with Zoom)  may provide easy access to such recordings and creating datasets suitable for AI.

Please cite the following reference if you have found this approach useful in your work: 

> MultiView Video capture with Zoom, R. Dahyot, April 2020, https://github.com/Roznn/MultiView-Video-capture-with-Zoom

```
@misc{RzDMVidZoomCapture,
title={MultiView Video capture with Zoom},
author={R. Dahyot},
year={2020},
howpublished = {https://github.com/Roznn/MultiView-Video-capture-with-Zoom},
note={DIY Computer vision at home},
}
```
