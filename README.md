# HomeAssistant_configuration
@SePo Lab - Sebastian - Tri Nguyen
Facebook: Sebastian Podiago
Email: tringuyen1506@gmail.com

This is contain whole setup of homeassistant server side.
Please review: Home Assistant System v1.0.0 04221017.pdf
Required version proposal : Home Assistant version 0.42.4
Wireless Network: WiFi + Bluetooth
Data transfer protocol: MQTT Broker http://mqtt.org/


Configration:
- Install Home Assistant following https://home-assistant.io/getting-started/, pick up 0.42.4
- My cases in virtual environment based on Raspbian Pi3
- update homeassistant configuration folder with below .yaml file
- For Air Conditioner platform, I re-coded default heatpump.py to ACControllMQTT_Sepo.py that can support control Air Conditioner via MQTT broker in JSON format. More details: vuiew project ACControllMQTT

New features:
- Actionable Notification on iOS app
- Slipt default configuration.yaml to smaller files .yaml to easy tracking

For explanation:
- Customize.yaml: GUI edit. REfer to: https://home-assistant.io/docs/configuration/customizing-devices/
- Device_tracker.yaml: tracking device connect to local network via Mac Address. REfer to: https://home-assistant.io/components/device_tracker.nmap_tracker/
- Camera.yaml: camera connection: foscam IP camera. Refer to: https://home-assistant.io/components/camera/
- Climate.yaml: Air Condiditioner controller. REfer to:https://home-assistant.io/components/climate/
- Group.yaml: Group sensor and device follow Zone. REfer to:https://home-assistant.io/components/group/
- iOS.yaml: config Push Notifcation and actionable category. REfer to:https://home-assistant.io/docs/ecosystem/ios/
- Binary_sensor.yaml: config sensor that have ON/OFF true/false index. REfer to:https://home-assistant.io/components/binary_sensor.mqtt/
- Sensor.yaml:config sensor that include numberize index. Refer to:https://home-assistant.io/components/sensor.mqtt/
- switch.yaml: config switch. REfer to: https://home-assistant.io/components/switch.mqtt/
