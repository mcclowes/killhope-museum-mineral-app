# GP_Killhope_Museum_App
Mobile application for Killhope Mining Museum


## Using Cordova
Basic guide to install, etc. - http://cordova.apache.org/docs/en/4.0.0//guide_cli_index.md.html#The%20Command-Line%20Interface

### Creating an app

    cordova create hello com.example.hello HelloWorld

### Adding a platform
Navigate to directory of project

    cordova platform add ios
    cordova platform add android

Substitute ios with relevant platform (though only need ios and android).
To remove one:

    cordova platform remove ios
    cordova platform remove android

### Building the project

    cordova build

or

    cordova build ios

Which comprises of:

    cordova prepare ios
    cordova compile ios

### Running the project
#### Through Emulation:
    cordova emulate android

### Through a device:
    cordova run android

## Using plugins
You can use plugins. We can look into this where appropriate.