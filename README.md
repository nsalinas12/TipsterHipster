# TipsterHipster
FBU Assignment Day 1


# Project 1 - *TipsterHipster*

**TipsterHipster** is a tip calculator application for iOS.

Submitted by: **Nico Salinas**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is complete:

* [X] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [ ] Settings page to change the default tip percentage.
* [X] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [X] User can enter subtotal separate from tax
- [X] User can place the tip rate on the subtotal price
- [X] User can choose to pay double the tax as the form of tip
- [X] UI animation hides the other value when entering subtotal and tax

## Video Walkthrough

Here's a walkthrough of implemented user stories:

Click here for the video [Walkthrough](https://imgur.com/a/LFLhPYG)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

One of the main problems I faced in this project was distinguishing the double tax button as a rate versus a cash value. For example, if the tax entered was $3, it would take the tip percentage to be 300% and the output would be totally wrong. Another error I faced was with the animations when I connected certain animations to the wrong methods, and it would result in certain methods being used twice and others used once.

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.
- None

## License

    Copyright 2018 Nicholas Salinas

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
