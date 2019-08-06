# Firebase Remote Commands

A [Firebase](https://firebase.google.com/docs/analytics/ios/start) integration with the [Tealium SDK](https://github.com/tealium/tealium-swift) that enables Firebase API calls to be made through  Tealium's [track](https://docs.tealium.com/platforms/swift/track/) API.

## Getting Started

Clone this repo and execute the `pod install` command in the project directory. You can then run the sample app to get an idea of the functionality.

> Note: Please navigate to the Keys folder within the TealiumFirebaseExample project and delete the file titled _REPLACE-ME.md_. Replace this file with the _GoogleService-Info.plist_ from your Firebase Console. Information about how to retrieve this file is located [here](https://firebase.google.com/docs/ios/setup#add-config-file).

### Prerequisites

* Tealium IQ account
* Firebase account 

### Installing

To include the remote command files in your own project, simply clone this repo and drag the files within the Sources folder into your project. 

Include the [Tealium Swift](https://docs.tealium.com/platforms/swift/install/) and [Firebase](https://firebase.google.com/docs/analytics/ios/start) frameworks in your project through your desired dependency manager.

Configure the Tealium IQ _Firebase Mobile Remote Command_ tag, send [track](https://docs.tealium.com/platforms/swift/track/) calls with any applicable data and validate in your [Firebase Console](https://console.firebase.google.com/).

## License

Use of this software is subject to the terms and conditions of the license agreement contained in the file titled [LICENSE.txt](LICENSE.txt). Please read the license before downloading or using any of the files contained in this repository. By downloading or using any of these files, you are agreeing to be bound by and comply with the license agreement.

___

Copyright (C) 2012-2019, Tealium Inc.

