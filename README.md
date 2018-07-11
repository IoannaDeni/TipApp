# Pre-work - *Tip Calculator*

**Tip Calculator** is a tip calculator application for iOS.

Submitted by: **Ioanna Deni**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [ ] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!
* Addition of picture for aesthetic. 
* Keyboard is numeric.
* Keyboard disappears when the screen is touched/clicked.
* In the text field that the bill is entered there is a demonstration of a bill of zero dollars
* If the user enters an invalid amount then the bill is converted to zero dollars
* The text field that the bill is entered clears automatically after tapping on the screen and then tapping back on the text field

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/gyXWPdh.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Learning to use the features and interface of Xcode was an interesting and not extremely demanding task. Further, swift is very similar to java, having weak and strong decleration of variables as well as outlets and let reminds us of public/private static and only type specific variable decleration in java.
The one difficulty with the interface are the "connections" that are automatically build once you drag an object onto another one or a part of code. If we attemp to delete a part of code or comment it out, logically assuming the "connection" is lost once the code is inactive the program will compile but fail to run givving a SIGABRT thread exception. It seems like that the connections between the object are not deleted which throws the exception. The way to solve this is to select the object and in the "properties" tab on the far right if the screen hit the arrow which will show the "connection", it had reference outlets, delegate. There if we wish to delete an object, or code connecting objects we need to press the x on the connecting pathways to eliminate the SIGABRT thread.

## License

Copyright 2018 Ioanna Deni

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
