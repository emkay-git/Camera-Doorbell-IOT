# Camera-Doorbell-IOT
If anyone rings the bell then this program will send the sms to the house person and he/she can see the live stream 
as to who is in front of the door.

Right now video stream part is complete.</br>
**Video Stream** is done on the local network using Flask and Opencv. Flask to create a local server and Opencv to grab the frame from
the camera and send it to the front end for person to see. Camera was attached to the Pi and other person on the same network
can see the video stream.</br>
Following video shows the working of video stream (from laptop, although it works on Raspberry Pi, but is not currently available
with me, will update the video with Raspberry Pi later)

</br>
<p align="center">
<a href="https://youtu.be/MC7w6f2B7iU">
<img src="https://img.youtube.com/vi/MC7w6f2B7iU/0.jpg" /> </a>
</p>  



## Usage
1. Run the python script from the terminal as `python stream.py`
2. Open up the browser on your system which is on the same network to see the streaming video.</br>
**Caveat**: Right now code has localhost as the server address, you need to change it to your ip to make it work on the local 
network, or else to see the results you can open the browser on your system.

## Suggested Improvement(s)

1. Turning off camera is not clean. Sometimes camera is on even after closing tab. It needs to be ammend.
1. SMS facility has to be added on this project.
2. Actual use will require it to host on internet, so that's something extra that can be done.
3. Face Recognition can be used so that SMS can also send some info about the person as to who is one the door than just
telling someone's on the door.
4. More options on the video streaming side can be made availble. Right now it's simply video streaming. So for example
Voice transfer can be integrated as well.

## Contribute
Doorbell integration with Pi hasn't been done yet. If you have done something similar, do share it with me by opening an issue may be.
You can give further ideas in this project. Fork it, send pull requsts, open issues and contribute freely.

## License
This project is licensed under [MIT License](https://github.com/emkay-git/Camera-Doorbell-IOT/blob/master/LICENSE)


