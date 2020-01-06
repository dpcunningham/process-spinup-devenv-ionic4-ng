# process-spinup-devenv-ionic4-ng-on-linux
Process: Spin Up a Development Environment for Ionic 4 (default Angular) Apps on a Linux (Mint 19) Platform.

I found the documentation required to spin up a development environment for Ionic mobile apps... anemic at best.  

The intro docs & tutorials (such as: [Get started with Ionic](https://ionicframework.com/getting-started) ) were very weak sauce. There were a few much higher quality resouces in the developer communituy (such as [Ionic Academy](https://ionicacademy.com/)) but even [their introductory turorials](https://ionicacademy.com/getting-started-with-ionic-4/) gloss over many of the gory details invvolved in resolving the many intersecting factors that arise in the complex develppment environment required to produce mobile apps for the Android platform.  

The process to ferret out these development cycle gotchas was extremely time consuming.  I don't like wasting the time of my development teams.  And I don't think that _"learning to take your lumps as a developer"_ is constructive either.  So I decided to collect all the "run off the runway into the weeds" stuff into one (hopefully useful) reference.  

This guide should enable any developer with reasaonable level of Unix/Linux experience to get up to speed on developing Ionic apps for Android devices without wasting enourmous amounts of valuable time.  

This guide presents every action-item in the "mental pipeline" as a GH issue:

- [survey: WTF is Ionic?](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/1)

- [explain: WTF use Ionic?](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/2)

- [understand: Background/History of Ionic](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/3)

- [watch (~14m): Introductory Ionic Video](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/5)

- [install: Node.js, npm, and ionic](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/4)

- [upgrade: Node.js (and npm) to their latest versions](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/6)

- [install: cordova](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/8)

- **[exercise 1: A basic Ionic4 "hello world" starter PWA (no IDE required)](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/7)**

- [understand: The Ionic CLI-driven "start... serve" cycle](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/10)

- **[exercise 2: simple button event processing w/ deployment onto Ionic Lab View Server](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/13)**

- [install: Android Studio (and various Java-related dependencies)](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/14)

- [install: Oracle JDK V8 (required for Android Studio builds)](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/15)

- [install: Gradle CI/CD pipeline tools (required for Ionic Android Studio builds)](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/16)

- [resolve: Ionic Android Build Errors](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/17)

- **[exercise 3: Build & deploy simple button event processing app onto Android device](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/18)**


There are a few other "farther horizon" issues (important, but not strictly required) recorded as well:


- [install/configure: git & GitHub in coordination w/ Ionic workflows](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/12)

- [review: Apache Cordova (underlying framework for hybrid mobile apps)](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/11)

- [survey: Quick Testing using Ionic Framework CDN](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/9)

- [install: cordova (needs review/modification, b/c my install was rather janky)](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/8)

- [Question: Does installing multiple SDKs cause multiple build targets/results?](https://github.com/dpcunningham/process-spinup-devenv-ionic4-ng-on-linux/issues/17#issuecomment-569389790)


