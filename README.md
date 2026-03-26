This project is an ESP32-based IoT system that connects to Wi-Fi and uses MQTT communication to control a buzzer and read keypad inputs.
The ESP32 subscribes to a topic to receive JSON commands for turning the buzzer ON or OFF,
and publishes keypad presses as JSON messages to another topic.
It demonstrates real-time publish/subscribe communication between hardware and a cloud-based MQTT broker.
