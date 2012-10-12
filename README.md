Android-Hello-World
===================

## Notes

* This application was built for the Nexus 7, and is locked in landscape orientation. Understandably, many device screens will not like the layout. Feel free to tinker around with the view in res/layout/activity_main.xml
* Please let me know if/how this app crashes on your Android device. We use the Camera and MediaRecorder Android classes and I expect there will be some native issues from device to device
* You may need to create a new token/session to connect. Visit our token generation page if this is the case: http://www.tokbox.com/opentok/api/tools/generator
* There is javadoc for the SDK in libs/opentok-android-sdk-docs. The API for the SDK is not complete; this build is meant to evaluate hardware, not build comprehensive applications.
* AVD/emulator will not work at this time.
* The SDK generates quite a bit of logging. Every logging tag starts with "opentok-", so you should be able to filter it out easily enough while debugging.
