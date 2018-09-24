# Create a “Copy Path” Service for the Right-Click Menu

If you find yourself frequently needing to copy and paste file and folder paths, creating an Automator Service will make your life easier because the service then becomes accessible from the OS X Right-Click contextual menu, accessible from anywhere in the Finder. This is an excellent trick from CNet and is very easy to set up yourself:

### Automator Service

Launch Automator and create a new “Service”
Use the search function to look for “Copy to Clipboard” and drag that into the rightside panel of the Service
Set ‘Service recieves selected’ to “files or folders” and ‘in’ to “Finder” as shown in the screen shot below
Save the Service with a name like “Copy Path”
