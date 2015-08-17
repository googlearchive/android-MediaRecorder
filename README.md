
Android MediaRecorder Sample
===================================

This sample uses the camera/camcorder as the A/V source for the MediaRecorder API.
A TextureView is used as the camera preview which limits the code to API 14+. This
can be easily replaced with a SurfaceView to run on older devices.

Introduction
------------

This sample shows how to use the [MediaRecorder][1] API.
It uses the [Camera][2] as input source and displays a preview on a [TextureView][3]
The sample features a button to capture the input and stop capturing afterwards.

It demonstrates how to correctly gain control and release the camera.
The sample also shows how to save the captured audio and video to persistant storage
and basic error handling.


[1]: https://developer.android.com/reference/android/media/MediaRecorder.html
[2]: https://developer.android.com/reference/android/graphics/Camera.html
[3]: https://developer.android.com/reference/android/view/TextureView.html

Pre-requisites
--------------

- Android SDK v23
- Android Build Tools v23.0.0
- Android Support Repository

Screenshots
-------------

<img src="screenshots/screenshot1.png" height="400" alt="Screenshot"/> <img src="screenshots/screenshot2.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-MediaRecorder

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2014 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
