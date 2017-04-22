# HomeAssistant_configuration
@SePo Lab
This is contain whole setup of homeassistant server side.
Required version: Home Assistant version 0.42.4

Configration:
- Install Home Assistant following https://home-assistant.io/getting-started/, pick up 0.42.4
- My cases in virtual environment based on Raspbian Pi3
- update homeassistant configuration folder with below .yaml file
- For Air Conditioner platform, I re-coded default heatpump.py to ACControllMQTT_Sepo.py that can support control Air Conditioner via MQTT broker in JSON format. More details: vuiew project ACControllMQTT

New features:
- Actionable Notification on iOS app
- Slipt default configuration.yaml to smaller files .yaml to easy tracking
