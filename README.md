# AmpMediaAnalytics

Akamai Adaptive Media Player is a media player for iOS and tvOS. Akamai AMP can manage different plugins like Chromecast Playback, Akamai Media Analytics, ComScore, and 360.

Avoiding manual implementation of media-related beacons is this module’s goal, our implementation uses our own AMP callbacks to notify Media Analytics so you don’t have to.

## Installation
---
### Cocoapods
[CocoaPods](https://cocoapods.org) is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate Alamofire into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
pod 'AmpMediaAnalytics'
```

### Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks. To integrate Alamofire into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
binary "https://mdtp-a.akamaihd.net/amp-ios-sdk/frameworks/AmpMediaAnalytics.json"
```

### Swift Package Manager
The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler. It is in early development.

To add a package dependency to your Xcode project, select File > Swift Packages > Add Package Dependency and enter its repository URL.

![Install Step 1](install1.png)

Then Add the following url:

```
https://github.com/akamai/ampmediaanalytics-package.git
```

# Akamai Media Player License Agreement
This is a License Agreement (the "Agreement") for certain software modules owned by Akamai Technologies, Inc. ("Akamai") that are used with the Akamai Media Player service offering in all available formats (the “Software”). Some license terms may only apply to the Akamai Media Player for a particular format, in which case the format for those terms will be explicitly stated.
Please read this Agreement. By using the Software, or enabling end-users to access the Software from your web property or any other distribution mechanism, you agree to these terms. If you do not agree to the terms of this Agreement, the Software cannot be deployed onto your website, distributed to end-users, or otherwise used for any purpose.
The Software consists of the Akamai Media Player iOS SDK and the following binaries for the Adobe Flash version: a) MDTBasicPlayer.swf, b) playerProductInstall.swf, and c) MDTPlayerConsole.swf. These computer programs are provided to you and your end- users in machine-readable (executable) form only. Akamai either owns or has the right to provide you the Software, portions of which may be copyrighted. The Software is provided at the cost set forth in the applicable Akamai services order form

1. Limited License. You have a non-exclusive, personal and non-transferable right and license to: a) use the Software to deliver and control video and/or audio content to your end-users, and b) use the the Media Analytics client in the Software in conjunction with the Software subject to you having separately contracted for Akamai’s Media Analytics service. If the Media Analytics component of the Akamai Media Player is used, it will be subject to all the terms of the applicable license. Akamai shall have the right to modify the Software at any time within its discretion. If you want to receive updated versions of the Software you must contract with Akamai for the Akamai Media Player Maintenance service for your particular player format. If you have the maintenance contract, updated versions of the Software shall be made available as soon as reasonably practicable to ensure that end-users implement such versions. You will ensure that anyone who obtains and uses the Software does so only in compliance with the terms of this Agreement. No right to sublicense is granted, and Akamai may terminate this license at any time upon notice to you. All other rights in and to the Software are hereby reserved. This license may be updated to accommodate licensing of new features of the Software, including but not limited to, new supported formats.
2. Restrictions.
    a. <ins>Personally Identifiable Information.</ins> You will ensure that your use of the Software does not provide Akamai with any personally identifiable information (PII), or any other information that can be used to uniquely identify, contact, or locate a single person or can be used with other sources to uniquely identify a single individual. Further, Akamai assumes no obligation and is not responsible to obtain end-user consent or approval for use of the Software.
    b. <ins>Third Party Use, Reverse Engineering or Export.</ins> You may not use, copy, modify or distribute the Software except as provided in this Agreement. Except as set forth herein, the Software may not be used in association with any third party product or service including, without limitation, any third party content delivery network (CDN). Except as permitted by applicable law and this Agreement, neither you, nor your end-users, may decompile, reverse engineer, disassemble, modify, rent, lease, loan, distribute, sublicense, or create derivative works from, the Software or transmit the Software over a network. You may not use or otherwise export the Software except as authorized by United States law and the laws of the jurisdiction in which the Software was obtained. In particular, but without limitation, none of the Software may be used or otherwise exported or re-exported (a) into (or to a national or resident of) a United States embargoed country or (b) to anyone on the U.S. Treasury Department's list of Specially Designated Nationals or the U.S. Department of Commerce's Table of Denial Orders. By using the Software, you represent and warrant that you are not located in, under control of, or a national or resident of any country or on any such list.
3. <ins>No Warranty On Software.</ins> You and your end users use the Software at your own risk. Akamai provides the Software to you "AS IS" and without warranty. You are not entitled to any hard copy documentation, maintenance, support or updates for the Software.

    AKAMAI EXPRESSLY DISCLAIMS ALL WARRANTIES RELATED TO THE SOFTWARE, EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. AKAMAI DOES NOT WARRANT THAT THE FUNCTIONS CONTAINED IN THE SOFTWARE WILL MEET YOUR REQUIREMENTS, OR THAT THE OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT DEFECTS IN THE SOFTWARE WILL BE CORRECTED. FURTHERMORE, AKAMAI DOES NOT WARRANT OR MAKE ANY REPRESENTATIONS REGARDING THE USE OR THE RESULTS OF THE USE OF THE SOFTWARE OR RELATED DOCUMENTATION IN TERMS OF THEIR CORRECTNESS, ACCURACY, RELIABILITY OR OTHERWISE. SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OF IMPLIED WARRANTIES, SO PORTIONS OF THE ABOVE EXCLUSION MAY NOT APPLY TO YOU.

4. <ins>Limitation Of Liability.</ins> In no event shall Akamai be liable to you for any damages exceeding any amount paid for the Software or the service with which the Software is used.
UNDER NO CIRCUMSTANCES, INCLUDING NEGLIGENCE, SHALL AKAMAI BE LIABLE FOR ANY INCIDENTAL, SPECIAL, INDIRECT OR CONSEQUENTIAL DAMAGES ARISING OUT OF OR RELATING TO THIS LICENSE, INCLUDING, BUT NOT LIMITED TO, DAMAGES RESULTING FROM ANY LOSS OF DATA CAUSED BY THE SOFTWARE. SOME JURISDICTIONS DO NOT ALLOW THE LIMITATION OF INCIDENTAL OR CONSEQUENTIAL DAMAGES SO THIS LIMITATION MAY NOT APPLY TO YOU.

5. <ins>Government End Users.</ins> If you are acquiring the Software on behalf of any part of the United States Government, the following provisions apply. The Software and accompanying documentation are deemed to be "commercial computer software" and "commercial computer software documentation," respectively, pursuant to DFAR Section 227.7202 and FAR 12.212(b), as applicable. Any use, modification, reproduction, release, performance, display or disclosure of the Software and/or the accompanying documentation by the U.S. Government or any of its agencies shall be governed solely by the terms of this Agreement and shall be prohibited except to the extent expressly permitted by the terms of this Agreement. Any technical data provided that is not covered by the above provisions is deemed to be "technical data-commercial items" pursuant to DFAR Section 227.7015(a). Any use, modification, reproduction, release, performance, display or disclosure of such technical data shall be governed by the terms of DFAR Section 220.7015(b).

6. <ins>Controlling Law and Severability.</ins>This Agreement shall be governed by the laws of the United States and those of the Commonwealth of Massachusetts. If for any reason a court of competent jurisdiction finds any provision, or portion thereof, to be unenforceable, the remainder of this Agreement shall continue in full force and effect.

7. <ins>Complete Agreement.</ins> This Agreement constitutes the entire agreement between the parties with respect to the subject matter hereof and supersedes all prior or contemporaneous understandings regarding such subject matter. No amendment to or modification of this Agreement will be binding unless in writing

Your rights under this Agreement will terminate automatically without notice if you fail to comply with any term(s) of this Agreement.

You may continue to license the Software under this Agreement for so long as you are using one of more of Akamai’s compatible video delivery services, or as Akamai shall otherwise agree in writing. Upon termination, neither you nor your end users will have the right to use the Software.
