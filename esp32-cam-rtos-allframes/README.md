# ESP32 MJPEG Multiclient Streaming All Frames Server

This is a MJPEG streaming webserver implemented for AI-Thinker ESP32-CAM or ESP-EYE modules. 

This is tested to work with **VLC** and **Blynk** video widget. 



**This version uses FreeRTOS tasks to enable streaming to up to 10 connected clients and is buffering and sending every frame to every client** 



Inspired by and based on this Instructable: [$9 RTSP Video Streamer Using the ESP32-CAM Board](https://www.instructables.com/id/9-RTSP-Video-Streamer-Using-the-ESP32-CAM-Board/)



