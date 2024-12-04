# Expo Camera focusAsync Issue

This repository demonstrates a bug in Expo's Camera component where `focusAsync` fails to function correctly when `autoFocus` is set to `'off'`. The camera preview might appear focused, but images captured using `takePictureAsync` will be blurry.

## Bug Reproduction

The `bug.js` file contains code to reproduce the issue. Run the app and try capturing an image; it will likely be out of focus despite the preview seemingly being sharp.

## Solution

The `bugSolution.js` file offers a potential workaround to mitigate the issue.  This solution often involves using a different approach to manual focus, perhaps using a custom focus mechanism or exploring alternative camera libraries if the problem persists.

## Environment

* Expo SDK: [Insert your Expo SDK version]
* React Native version: [Insert your React Native version]
* Device/Emulator: [Insert device/emulator details]