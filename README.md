# Uploader


Uploader is a free very simple and customizable html5 avatar uploader that you can easily integrate in your projects.



## Settings

### Basic Settings
* name ("photo") : name sent in the POST request
* basePhoto ("") : the default photo displayed at the beginning
* postUrl ("") : the url to which is sent the POST request
* imageTypes" (["image/jpeg","image/png"]) : the accepted images types
* maxSize (null) : The max image size

### Advanced Settings
* onClientAbort
* onClientError
* onClientLoad
* onClientLoadEnd
* onClientLoadStart
* onClientProgress
* onServerAbort
* onServerError
* onServerLoad
* onServerLoadStart
* onServerProgress
* onServerReadyStateChange
* onSuccess


## Dependency

Uploader is written in plain javascript.
It depends on :

* [Classie.js](https://github.com/desandro/classie) for class helper functions.
