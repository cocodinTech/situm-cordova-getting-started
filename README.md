#Situm Cordova Getting Started

NOTE: This app is only a use-case for testing purposes. It may not be up to date or optimized.

1) Ionic installation : https://ionicframework.com/docs/intro/installation/

2) Link development plugin folder: 

cd situm-cordova-android-getting-started
cordova plugin add --link <path_to_plugin_folder>/situm-cordova-plugin/

So, config.xml file should contain one line like this:

    <plugin name="situm-cordova-plugin" spec="file:../situm-cordova-plugin" />


>Run Android version:

- Run from command line :

ionic cordova run android


- Run from Android Studio

Go to plaftforms/android folder. Create android studio project and run MainActivity class


>Run IOS version:

-This plugin is still in development