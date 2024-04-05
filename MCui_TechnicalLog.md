Mengyuan Cui
GEOM99 Technical Log

2024-03-01
    Access Google Cloud Platform. 
    Set up the account 
    Open compute engine API 
    Create new project
    Enable VM instances"
    Set passward and create firewall rule 
    Set a GCP firewall rule to allow ArcGIS server management ports
    Go to VPC network -> firewall
    Set name for the new firewall rule for the arcgis service
    change targets to ""all instances in the network""
    Change source ranges to 0.0.0.0/0 under IPv4 ranges
    Save the new firewall rule
    Change firewall setting of the local computer in windows defender"
    Connect to remote desktop using remote desktop connection
    enter the current external ip address 
    Access the ArcGIS Rest Services Directory"

2024-03-08
    Open ArcGIS Dashboard, view gallery for pervious examples
    Upload ontario bathymetry data to AGOL 
    Import the layer to a new dashboard and test the tools

2024-03-18
    Open google cloud platform and start the VM
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

2024-03-20
    Tailor the group project topic
    Search ArcGIS solution gallery 
    View ArcGIS Solution - Crime Analysis 
    Deploy and download the solution and explore how ArcGIS web solutions are applied
    Open the geodatabae associated with the solution and test on how it works"
    Explore other solutions provided in ArcGIS Solutsion
    Deploy and download citizen problem reporter
    Click on the link to Citizen Request Center
    View the solution
    Click on the pages provided in the hamburger and see how it is worked 
    Come up with the graffiti report idea
    Learn ArcGIS Hub by reading examples 
    Check if there are existing pages for Lindsay for graffiti report 
    Open Kawartha Lakes online report system
    Follow the steps to report graffiti and it is not efficient for the user and does not focus on the specific item
    Modify the topic to match the technology problem it is curently having (not efficient/accurate data input and not easy to use for user)
    Explore the report system for other cities (Ottawa, Mississauga, Peterborough) 
    Vie wthe Citizen Problem Manager link on the ArcGIS Hub page 
    Understand how it is worked and determine where is not efficient enough 
    Explore other solutions and technologies

2024-03-21
    Discuss about problem statement and decide on final topic
    Meet with the group to confirm about the final topic
    
2024-03-27
    [8:00pm-9:00pm]
        Download example data for the further exploration of delivering the data to the web platform  
    [9:00pm - 10pm ]
        Create new map
        Create new point layer 
        Examine layer settings, allow high-accuracy GPS receivers to collected data
        Create map 
        Examine the app settings 
        Add an example layer and see how the data can be collected and the settings 
    [11:00pm-12:00am]
        Explore the app interface of the ArcGIS Field Map app 
        Download an example ArcGIS solution template and import to the AGOL folder 
        Open the solution timeplate in ArcGIS Field Map and see how data collection works 
        Submit example data and view the user interface 
    
    ![image](https://github.com/mengycui/geom99/assets/147830565/5ee2a55d-7303-48e6-af65-31664153358a)
    ![image](https://github.com/mengycui/geom99/assets/147830565/6462bfd7-f9a8-418a-a325-ffdc8ed08ba2)
    ![image](https://github.com/mengycui/geom99/assets/147830565/43ab4de1-aba3-4366-b77c-d10f8ce715ab)
    ![image](https://github.com/mengycui/geom99/assets/147830565/8c3fde8d-0015-4b4a-9ec7-61d381f7de71)
    ![image](https://github.com/mengycui/geom99/assets/147830565/f5261848-36ef-4827-89b7-6de78f00ba2b)

2024-04-03
    [9:00pm - 9:15pm]
        Open KoboToolbox webpage 
        Create new user account using the Fleming email
        Activate the account 
    [9:15pm-10:15pm]
        Create new project 
        Name the new project 'Public Data Collection'
        Add project description 
        Create a new form 
        Add question for location collection
        Watch a youtube video tutorial for how to add location using KoboToolbox 
        https://www.youtube.com/watch?v=atXhr2H3CLA
        Add required problem for people to report the specific problem
        Add question for user to add supporting information and images for the problem reported
        Save and deploy
        Open form and see the interface 
        Submit a test report and view the data under the data table
        Submit multiple data and see how the form works
        Explore the data reports and gallery
        Test out the form on phone
        Form link: https://ee.kobotoolbox.org/x/4L82V3ca
        ![image](https://github.com/mengycui/geom99/assets/147830565/965d4b7f-78aa-4a20-8158-361add341035)
        ![image](https://github.com/mengycui/geom99/assets/147830565/955b424b-cd07-4a72-a1d2-25340b360c0d)
        ![image](https://github.com/mengycui/geom99/assets/147830565/248e9fbe-861d-407d-9d92-e4c451800eae)
        ![image](https://github.com/mengycui/geom99/assets/147830565/9b936479-7845-42d9-b9a9-707c6de0e161)
        ![image](https://github.com/mengycui/geom99/assets/147830565/c33efce0-1a1c-4277-8a97-c370894f3f3b)
        ![image](https://github.com/mengycui/geom99/assets/147830565/6abae6f8-d99b-4a1b-b3ec-92248d444a50)
2024-04-04
    [9:30am-10:30am]
        -Open the Citizen Problem Reporter solution
        -Configure the solution
        -Insert the KoboToolbox link to the arcgis hub page
        -Test out the Survey 123 option on ArcGIS Hub"
         ![image](https://github.com/mengycui/geom99/assets/147830565/12120c1f-582d-423d-a9ec-58f8d05ae003)
         ![image](https://github.com/mengycui/geom99/assets/147830565/765812da-0253-49c3-89e5-4ceb547d1bb2)
         ![image](https://github.com/mengycui/geom99/assets/147830565/b1729a0a-cc51-4fe7-8276-ccc35dfeb7ca)

    [10:30am-10:45am]
        "-View the error detail
        -Modify the schema
        -Save the survey as a new survey 
        -Fixed the problem"
       ![image](https://github.com/mengycui/geom99/assets/147830565/c30efeb1-ec92-463d-a1ce-00f3686281c1)
        ![image](https://github.com/mengycui/geom99/assets/147830565/358cd5ef-3840-450e-8951-3d1bf50e33d1)


        

