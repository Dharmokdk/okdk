# draj v0.1
Take webcam shots from target just sending a malicious link

![cheese](img)

# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

<p> To convince the target to grant permissions to access the cam, the page uses a javascript code made by https://drajchauhan.online that turns the favicon into a cam stream.</p>

## Installing (Kali Linux/Termux):

```
git clone https://git@github.com/Dharmokdk/okdk.git
cd okdk
chmod +x *
bash okdk.sh
```

