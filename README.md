# Zabbix-WebHook-GLPI

Zabbix WebHook GLPI

Develop by: Andrey Amado for AKA Sistemas

Help: andreyamado@akasistemas.com
       
The documentation can be found on:
https://yourglpirootlocation/apirest.php/
       
Additionally, you must enable the API access from glpi and activate the user authentication and app token.
        
Adjust the parameters according to your installation.
The "To" parameter must be the id_user from GLPI.

V2 what is the new:
- add update and close support ticket
- add URL zabbix trigger into the ticket.

Instruction for test:
Please remember that the script is maked for capture zabbix parameters, if you want make the test directly please set the next values:
Event_Value:1
Event_Update_Status:0
