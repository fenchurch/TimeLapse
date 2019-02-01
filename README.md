# TimeLapse

###### Sequentially grab images from mjpeg stream
---
1. Pull Single Images from ip camera MJpeg stream
    fmpeg -i "http://root:otto12@192.168.2.101/mjpg/video.mjpg" -vframes 1 test.jpg

2. Label them sequentially, either by id, or by date. Not sure yet.
3. Daily/Weekly/Monthly compilation into Video or zip of jpegs
4. Cron jobs for execution

ffmpeg dependent
