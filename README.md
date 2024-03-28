# Setup Instructions

1. **Network Connection**
   - Connect your PC and iPhone to the same network.

2. **Application Installation**
   - Install app app to iPhone/iPad.
     * Please contact me for the download link
     * LiDAR sensor is required.
   - Download the app for Looking Glass from this repository.
   - Download and install Looking Glass Bridge from the official website: [Looking Glass Bridge](https://lookingglassfactory.com/software/looking-glass-bridge).
   - Confirm your display setting. [Display Setting](https://docs.lookingglassfactory.com/software-tools/looking-glass-bridge/display-settings-on-windows)



# Application Usage

1. **Connect Devices**
   - Connect your PC and the Looking Glass Portrait using an HDMI cable.

2. **Launch Software**
   - Start the Looking Glass Bridge application.
   - Launch `DepthVideoPlayer.exe` or `DepthVideoPlayer.app` .
   - Ensure that the Looking Glass displays the PC's IP Address.

3. **Start the iPhone/iPad App**
   - Open the iPhone/iPad app.
   - Enter the IP Address in the app and tap the `Set` button.

4. **Recording**
   - Tap the `Rec` button to start recording.
     * The depth of the colored areas is recorded, while the depth of the distant scenes (gray areas) is not recorded.
     * The areas around the depth indicated by the blue line will be clearly displayed in the Looking Glass.
      <img src="https://github.com/TakashiYoshinaga/DepthVideoPlayer/blob/main/Materials/example.jpg?raw=true" width="200">
   - Tap the `Stop` button to end the recording.

5. **Playback**
   - The video with depth data will automatically be transferred to the PC and playback will begin.

# Add and Delete Video Files Manually

1. **File Storage Location on iPhone/iPad**
   - Go to Files app -> Depth Recorder -> Captures.
   - Delete files or transfer them to your PC as needed.

2. **File Storage Location on PC**
   - Windows: Inside the `dl` folder located in the same directory as DepthVideoPlayer.exe.
   - Mac: Inside the `dl` folder within DepthVideoPlayer.app.
  
# Real-time Communication App
If you are interested in real-time communication using Point Cloud, please try the app below.  
Note:  
In cases where communication might be hindered in environments with strict security, consider using tethering or similar alternatives.  
https://github.com/HoloTuberKit/HoloTuberKit-RealTime


