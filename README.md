# SamplePythonMQTT
Sample MQTT clients for Creating device type via API (WSO2 IOTS 3.1)

SampleClient :- Connects with the initial token which has a validity period of 1hr 
                Will not work if disconnetcs and connects again after token expired
                If client maintains the connection continously, It will continue to be connected even after 1hr 
                
SampleClient2 :- Take new access token each time it begins the execution 
                 So token expiration not be an issue
                 

Replace your config file with config.json file inside the Configuration folder
