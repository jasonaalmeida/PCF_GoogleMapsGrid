# PCF - Google Maps Grid
A PCF control to render a view of records on Google Maps using the location information (lat/long) againt each record.

## Features
- The control uses the columns in the view to display an information window when a location marker is clicked.
- The information window also includes a configurable title that will navigate the user to the respective record
- The control also requests your current location to display the map in the correct area. Location data is not transmitted externally. You can choose to deny this permission and the map will load at lat/long 0,0.

**NOTE:** You will need to provide a Google Maps API Key.

![Gmaps Preview](https://github.com/jasonaalmeida/PCF_GoogleMapsGrid/blob/master/GoogleMapsGrid/images/gmaps_preview.png)

## Configuration
Use the following steps to configure a Google Maps Grid against a view after installing the solution
1. Add the desired columns/filters to a view. Reember to include the respective latitude and longitude fields in the view. To keep things clean, the lat/long fields are ignored when displaying the information window
2. Click the 'Custom Control' button to add the control
3. Select the 'Google Maps Grid' control
4. Control parameters (Screenshot below):
   1. Primary Field - The logical name of the primary field to be used as the title for the information window when a marker is clicked
   2. Latitude Field - The logical name of the latitude field to be used to pin point the location of a particular record
   3. Longitude Field - The logical name of the longitude field to be used to pin point the location of a particular record
   4. Google Maps API Key - The API key to allow Google Maps to load

![GMaps Configuration](https://github.com/jasonaalmeida/PCF_GoogleMapsGrid/blob/master/GoogleMapsGrid/images/gmaps_config.png)

## CDS Solution
 For convienence, the Releases folder contains a managed solution that can be installed on CDS.