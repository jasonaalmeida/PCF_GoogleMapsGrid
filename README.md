# PCF - Google Maps Grid
A PCF control to render a view of records on Google Maps using the location information (lat/long) againt each record. 
The control also uses the columns in the view to display an information window when a location marker is clicked.
The information window also includes a configurable title that will navigate the user to the respective record
NOTE: You will need to provide a Google Maps API Key.

//image preview

## Configuration
Use the following steps to configure a Google Maps Grid against a view after installing the solution
1. Add the desired columns/filters to a view. Reember to include the respective latitude and longitude fields in the view. To keep things clean, the lat/long fields are ignored when displaying the information window
2. Click the 'Custom Control' button to add the control
3. Select the 'Google Maps Grid' control
4. Control parameters:
  a. Primary Field - The logical name of the primary field to be used as the title for the information window when a marker is clicked
  b. Latitude Field - The logical name of the latitude field to be used to pin point the location of a particular record
  c. Longitude Field - The logical name of the longitude field to be used to pin point the location of a particular record
  d. Google Maps API Key - The API key to allow Google Maps to load

//configuration image