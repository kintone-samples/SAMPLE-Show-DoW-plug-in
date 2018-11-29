# [Sample plug-in: Show DoW Plug-in]
## Purpose of the Sample Plug-in
This sample plug-in is available for educational purposes.  
Use this plug-in to understand how Kintone plug-ins work, and how they are structured.
A non-packaged version written with a single JavaScript file can be found here https://developer.kintone.io/hc/en-us/articles/115005449567

## What the plug-in does
This plug-in displays the day of the week next to the specified Date field in the record details view.
When a user saves a record with a Date field, the day of the week will be displayed inside of the date field in parentheses next to the date.
The plug-in settings page allows the user to choose which Date field will be used, as well as give the days of the week custom names.

## Plug-in directory structure
This sample plug-in is created with the following directory structure.

src/  
├── html/  
│        └──── config.html  
├── css/  
│        ├──── 51-modern-default.css  
│        └──── config.css  
├── js/  
│        ├──── config.js  
│        └──── desktop.js  
├── image/  
│        └──── dowicon.png  
└── manifest.json  

## How to use
To simply test out the plug-in on your Kintone domain, follow these steps:

1. Download the plug-in zip file  
Reference: https://github.com/kintone/SAMPLE-Show-DoW-plug-in/releases
2. Install the plug-in into your domain  
Reference: https://get.kintone.help/hc/en-us/articles/115001519707-Installing-Viewing-Plug-ins
3. Add the plug-in to a specific Kintone App  
Reference: https://get.kintone.help/hc/en-us/articles/115001511188-Adding-Plug-ins-to-an-App
4. Make sure that a Date field is placed in the form of your Kintone App. Access the plug-in settings, and enter in the neccessary settings. Save the settings, and update the App.
5. Click the + button on the Record List page to start adding a new record. Select a date from the Date field and save the record. The name of the day of the week that was specified in the settings will be displayed within the Date field.

## How to modify
1. Fork to your repo
2. Make changes to files under /src
3. Repackage the plug-in by:  
 i. Zipping the manifest.json file, css directory, html directory, image directory and js directory into one zip file.  
 ii. Drag and dropping the file into the [kintone plug-in packer](https://kintone.github.io/plugin-packer/).

## Pull Request Policy
As this repo exists for educational purposes, we will most likely turn down pull requests that contain updates with new features.  
Please feel free to host plug-ins with new features on your own repository.  
Bug fixes are happily accepted.

## More information
More information on the plug-in can be found here https://developer.kintone.io/hc/en-us/articles/360010076614
