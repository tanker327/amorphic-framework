## 1.1.40
* Added support for daemons (batch tasks)
## 1.1.38
* fixed problem referencing static assets for other than the default application
## 1.1.37
* schema.js and config.js can now be in /app/common
* fixed another issues with multiple applications
## 1.1.35
* Multiple applications had some path issues
## 1.1.35
* You can now place common template files in /app/common/js
## 1.1.33
* Include new dependencies
## 1.1.31
* Include model files as document.writes of the script files since source mapping would otherwise not be available
## 1.1.30
* Tests were not running because securityContext injected in supertype rather than peristor
## 1.1.28
* Corrected a problem when controllers are created on the server model was not being passed to client
## 1.1.27
* Include proper path for modules
* Fixed incorrect file upload handling
* Include controller and it's dependency automatically for the browser
Note:  You must remove any script statements to include the model as they are included automatically no
       when you include /amorphic/init