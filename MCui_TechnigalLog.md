Mengyuan Cui
GEOM99 Technical Log

2024-03-01
 Access Google Cloud Platform. 
 Set up the account 
 Open compute engine API 
 Create new project
 Enable VM instances"
 "Set passward and create firewall rule 
 Set a GCP firewall rule to allow ArcGIS server management ports
 Go to VPC network -> firewall
 Set name for the new firewall rule for the arcgis service
 change targets to ""all instances in the network""
 Change source ranges to 0.0.0.0/0 under IPv4 ranges
 Save the new firewall rule
 Change firewall setting of the local computer in windows defender"
 "Connect to remote desktop using remote desktop connection
 enter the current external ip address 
 Access the ArcGIS Rest Services Directory"

2024-03-08
 Open ArcGIS Dashboard, view gallery for pervious examples
 Upload ontario bathymetry data to AGOL 
 Import the layer to a new dashboard and test the tools

2024-03-18"Open google cloud platform and start the VM
 Connect to the remote descktop and access the Canada.zip data
 Download the data to the local disk
 Notice the Canada shapefile data was already in C drive within the gisserver folder
 Create a new project in ArcGIS Pro
 Open the Canada shapefile in the new project
 Create connection to the server 
 New ArcGIS server connection, use the external ip plus 6443 to connect to the server
 The authentication used is provided on D2L (siteadmin/Eclipse2024)
 Right click on the connected server, click on publish map service
 Name the map service as MCui_Canada, provide summary describing that the layer is a shapefile of Canada that includes Provinces 
 Add tag as geom99
 Click analyze and explore the errors and warnings
 Solve the error by let ArcGIS assign Unique IDs 
 Other warnings are about the projection of the layer 
 Tried to change the map projection (unnecessary) to solve the warning 
 Map projection changed to WGS 1984 Web Mercator 
 Publish map service to the server 
 Take screenshot for the working VM
 Take screenshot for the running VM on the google cloud platform
 Take screenshot for the published service workspace
 Take screenshot of the map service using ArcGIS JavaScript view as public user"
