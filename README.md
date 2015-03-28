# GP_Killhope_Museum_App
Mobile application for Killhope Mining Museum

[Colour pallete 1](http://www.colourlovers.com/palette/3691940/Killhope_1)


## Mineral JSON Objects
The .docx file given to us is rather inconsistent and obviously copied and pasted of wikipedia but I did my best to move it all to JSON format.

The JSON object for the minerals is an array of mineral objects each with 6 fields:
• Name of mineral
• Formula of mineral
• 4 'stages' of information about the mineral

Some strings are very long but none end with a '.'

### Stage 1
Colour(s) (JSON Array)
Abundance
Hardness
Lustre
Ore (Sometimes empty)
An 'ineresting' fact

### Stage 2
Uses
Main countries involved in the extraction of mineral (Sometimes empty)
Crystal Habit (Habit)
Crystal Structure (Structure)
Depositional Environment
Transparency
Origin of name
Colour(s) at Killhope

### Stage 3
Further Uses (Sometimes empty)
Streak
Cleavage
Fracture

### Stage 4
Specific Gravity
Further Properties (Often empty)
Tenacity (Often empty)
Relevance at Killhope
Optical Properties
Twinning (Often empty)
Impurities

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

#### Through a device:
    cordova run android

## Using plugins
You can use plugins. We can look into this where appropriate.
