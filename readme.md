<h1>Node-Red SubFlows for the Shelly i3 and Shelly Button1 devices to process MQTT packets.</h1>

* On the i3 you need to disable MQTT updates to stop false triggers -- http://deviceipgoeshere/settings?mqtt_update_period=0
* The MQTT input must register to recive all packets -- shellies/shellybutton1-deviceidgoeshere/#
* Device id can be found in Settings-> Device Info -> Device ID

![User Controls](/Shelly%20Node-Red.JPG)

![User Controls](/Shelly%20Button1%20Subflow.JPG)

![User Controls](/Shelly%20i3%20Subflow.JPG)

Hope this helps
Cheers
Tony
