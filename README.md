### MooTools FileManager - Copyright (c) 2009 [Christoph Pojer](http://og5.net/christoph)

A filemanager for the web based on MooTools that allows you to (pre)view, upload and modify files and folders via your browser.

### Demos

* Open the "Demos/" folder and have fun
* To test TinyMCE Download and extract it to "Demos/TinyMCE" and access "Demos/tinymce.html"

### Configurable Options
* See Source/FileManager.js and Backend/FileManager.php for all available options on the client- and server-side

### Installation
* See "Demos/index.html" for the clientside integration
* See "Demos/manager.php" or "Demos/selectImage.php" for serverside integration

### Custom Authentication
* As Flash and therefore the Uploader ignores authenticated clients you need to specify your own authentication. In order to do this you need to provide a custom "UploadIsAuthenticated" function on the serverside and you need to specify "uploadAuthData" on the client.