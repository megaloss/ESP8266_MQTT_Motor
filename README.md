# ESP8266_MQTT_Motor


Control your linear actuator with dc motor through MQTT requests.
I use Amico ESP8266 based board with attached motorshield.
This motorshield uses for 1st motor D3 port to choosea a direction and D0 as PWM.
Instruction "/set" sets a position for linear actuator. Every time at start it closes completety to be aware of it's position. After getting a closing instruction it goes a little bit further (actuator has built-in stop connectors).
