# openhealth2

openhealth2

### After cloning:
Run the following in order:

'bower install' to install angular dependencies. If not previously installed, this may
take a while especially angularjs.

'npm install' to install gulp dependencies

1. 'bower install'
2. npm install

### Building the mobileangular app

NOTE: Before building, make sure all required platforms and plugins have been installed first. 
See Plugins and Platform sections below

'gulp build' will just build the latest javascript files from 'src'
folder and output them in 'www' folder.

'gulp' builds the javascript files as well as sets up an auto-rebuild
server that watches changes made to the files inside the 'src' folder

1. 'gulp build' or  just 'gulp'
2. 'cordova run' - run in browser

   'cordova run (android | iphone | platformX)' run app in the specified
   platform

### Logging methods
1. Android-level logging can be done using 'adb logcat | grep Console'. The
cordova specific activity is 'Web Console', where console.log's are outputted.
2. 'chrome://inspect' in google chrome. Haven't tried this yet. 
This is for android 4.4+ only

### Plugins:

Install the following cordova plugins:
* cordova-plugin-sms
* custom url scheme

### Platforms
To install on an android emulator or test phone, do

'cordova platform add android'

before compdiling with 'cordova build' or run...

### TODO:
* Make this code to be Service-Oriented Architecture, wherein 
components of the system communicate with each other using http
request API set by the component.
