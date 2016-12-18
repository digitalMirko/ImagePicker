# ImagePicker
Xcode 8.2 under Swift 3

### App that allows you to add photos from your "Photo Library" or "Camera" into your iOS app if you allow it to access those areas.

First launch the app.

Then click the "Choose Image" button located on the bottom of the app.

A Photo Source actionSheet box pops up from the bottom asking you to "Choose a source" from 3 options.

Option 1: "Camera", which accesses your camera to take a photo and then put it into your app. 
It first checks to see if the Camera app is available, if it is, it will ask you for permission to use it.
If it is not available, it will print out to the command console a message that the "Camera unit not available".

Option 2: "Photo Library", which accesses your Photo Library to put an image into your app.
It will ask you for permission to access your Photo Library. If you allow it to it will then proceed to add the image
that you choose to put into your app.

Option 3: "Cancel", cancels the Photo Source Action sheet box.
