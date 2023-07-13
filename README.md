# svejdarpaa_features
Base for some of other our scripts

This is base of our scripts: firing mode, gasmask

You have two possibilities how You can use our scripts:
1. start every scripts as single script - bad optimalization, many resources
2. start every scripts as one - better optimalization, one resource

Steps for use base:   
1. Drag the folder into your server
2. Write name of this resource into server.cfg
3. If the script have - ImportIntoDatabase.sql - import it into database
4. Restart the server
                      
Steps for adding a new our script into base:    
1. Copy client script named as c_*.lua into client folder
2. Copy server script named as s_*.lua into server folder
3. Write this files into fxmanifest.lua
4. If the script have - ImportIntoDatabase.sql - import it into database
5. Restart the server
                     
