
The app utilizes OpenSL ES for loopback audio.

Must have:
__________________________________________________________________________
- Android Studio 2.2+ with [NDK](https://developer.android.com/ndk/) bundle.

To Run: 
_________________________________________________________________________
1. [Download Android Studio](http://developer.android.com/sdk/index.html)
2. Launch Android Studio.
3. Open the sample directory.
4. Open *File/Project Structure...*
5 - Click *Download* or *Select NDK location*.
6. Click *Tools/Android/Sync Project with Gradle Files*.
7. Click *Run/Run 'app'*.

What the app does:
_________________________________________________________________________
App will capture audio from android devices and playback on the same device; 
the playback on speaker will be captured immediately and played back.
The latency will be displayed on the screen when the 'start' button is pressed.
It is recommended to wear a earphone to ensure a good audio quality.
