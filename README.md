# TimeLapse

###### Sequentially grab images from mjpeg stream
---
<<<<<<< HEAD
1. Pull Single Images from ip camera MJpeg stream:
=======
1. Pull Single Images from ip camera MJpeg stream
>>>>>>> 328af2a63ee544d948bf36fedddb4595d9b564ea

`fmpeg -i "http://root:password@192.168.1.1/mjpg/video.mjpg" -vframes 1 output.jpg`

2. Label them sequentially by epoch date.
3. Daily/Weekly/Monthly compilation into Video or zip of jpegs
4. Cron jobs for execution

ffmpeg dependent

