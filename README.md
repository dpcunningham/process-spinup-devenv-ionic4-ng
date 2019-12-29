# process-spinup-devenv-ionic4-ng-on-linux
Process: Spin Up a Development Environment for Ionic 4 (default Angular) Apps on a Linux (Mint 19) Platform

I found the documentation required to spin up a development environment for Ionic mobile apps... anemic at best.  

The intro docs & tutorials (such as: [Get started with Ionic](https://ionicframework.com/getting-started) ) were very weak sauce. There were a few much higher quality resouces in the developer communituy (such as [Ionic Academy](https://ionicacademy.com/)) but even [their introductory turorials](https://ionicacademy.com/getting-started-with-ionic-4/) gloss over many of the gory details invvolved in resolving the many intersecting factors that arise in the complex develppment environment required to produce mobile apps for the Android platform.  

The process to ferret out these development cycle gotchas was extremely time consuming.  I don't like wasting the time of my development teams.  And I don't think that _"learning to take your lumps as a developer"_ is constructive either.  So I decided to collect all the "run off the runway into the weeds" stuff into one (hopefully useful reference.  

This guide should facilitate any developer with reasaonable level of Unix/Linux erperience to get up to speed on developing Ionic apps for Android devices without wasting enourmous amounts of valuable time.  

I will develop this spin-up process in the style of the venerable Peter Hintjens, whereby every action-item in the "pipeline" is 
entered and resolved as an issue, viz:

- survey: WTF is Ionic?

- explain: WTF use Ionic?

- understand: Background/History of Ionic

- watch (~14m): Introductory Ionic Video

- install: Node.js, npm, and ionic

- upgrade: Node.js (and npm) to their latest versions

- install: cordova

- exercise 1: A basic Ionic4 "hello world" starter PWA (no IDE required)

- understand: The Ionic CLI-driven "start... serve" cycle

- exercise 2: simple button event processing w/ deployment onto Ionic Lab View Server

- install: Android Studio (and various Java-related dependencies)

- install: Oracle JDK V8 (required for Android Studio builds)

- install: Gradle CI/CD pipeline tools (required for Ionic Android Studio builds)

- resolve: Ionic Android Build Errors

- exercise 3: Build & deploy simple button event processing app onto Android devic


There are a few other "farther horizon" issues (important, but not strictly required) recorded as well:


- install/configure: git & GitHub in coordination w/ Ionic workflows

- review: Apache Cordova (underlying framework for hybrid mobile apps)

- survey: Quick Testing using Ionic Framework CDN

- install: cordova (needs review/modification, b/c my install was rather janky)

