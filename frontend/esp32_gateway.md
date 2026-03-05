# ESP32 Gateway

## Purpose
The ESP32 acts as an IoT gateway that collects data from farm sensors and sends it to the FarmGuard AI system.

## Connected Sensors
- Soil Moisture Sensor
- Soil pH Sensor
- Weather Sensor

## Workflow

1. Sensors collect environmental data from the farm.
2. ESP32 reads sensor values.
3. Data is transmitted to the cloud server.
4. Backend AI agents analyze the data.

## Example Data

{
  "soil_moisture": 45,
  "soil_ph": 6.5,
  "temperature": 28,
  "humidity": 60
}

## Technology

Microcontroller: ESP32  
Connectivity: WiFi  
Protocol: HTTP / MQTT
