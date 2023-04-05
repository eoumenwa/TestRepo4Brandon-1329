# TestRepo4Brandon-1329
When trying to add a repo to an existing Github connection we are getting errors every time. We use a single account for adding all these connections.  

 

Seemed to start around last week, normally this would work without getting this error.  

  

Error: Failed to save connection. VS403651: The connection does not exist or you do not have have permission to access it.  

  

This is occurring in our production instance and no changes to TFS/ADS or GIT have occurred in this time. No changes to the service account that sets up these connections. 

  

We checked permissions on both sides (GIT and ADS) nothing changed there. Also tried setting up a brand new connection which worked as intended and didn't error out when adding a repo. 


Testing PR 1 and 2 and 3
