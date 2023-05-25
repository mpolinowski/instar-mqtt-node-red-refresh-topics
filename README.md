# INSTAR MQTT

## Proof-of-Concept MQTT Auto-refresh (Node-RED)

* [INSTAR MQTTv5](https://wiki.instar.com/en/Advanced_User/INSTAR_MQTT_Broker/MQTTv5_API/).

### Live Video & Internal Sensors

Live video preview in form of a `base64` encoded snapshot and an refresh interval of 10s:


![Auto-Refreshing MQTT Topics in Node-RED](https://github.com/mpolinowski/instar-mqtt-node-red-refresh-topics/blob/master/assets/WQHD_MQTTv5_Autorefresh_Node-RED_02.webp)



### Camera Update

Get notified of and perform firmware updates using the MQTT API:


![Auto-Refreshing MQTT Topics in Node-RED](https://github.com/mpolinowski/instar-mqtt-node-red-refresh-topics/blob/master/assets/WQHD_MQTTv5_Autorefresh_Node-RED_03.gif)





### Node-RED

Import `node-red-flows.json` using the Node-RED import function:

![Auto-Refreshing MQTT Topics in Node-RED](https://github.com/mpolinowski/instar-mqtt-node-red-refresh-topics/blob/master/assets/WQHD_MQTTv5_Autorefresh_Node-RED_01.webp)
