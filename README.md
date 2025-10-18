# SOIL-IRRIGATION
Working of Automatic Irrigation System

The automatic irrigation system is designed to monitor the soil moisture level and automatically control the water supply to plants. The circuit mainly consists of soil moisture sensors, a comparator or microcontroller (like Arduino), a relay driver circuit, and a water pump.

Soil Moisture Sensing:
The soil moisture sensor (usually made of two probes or a resistive sensor) is inserted into the soil. It detects the water content by measuring the resistance between the probes — dry soil has high resistance, while wet soil has low resistance.

Signal Processing / Comparator:
The output of the moisture sensor is fed into a comparator circuit (often using an operational amplifier). The comparator compares the sensor voltage with a preset reference voltage that represents the desired soil moisture level.

Control Decision:

When the soil is dry, the sensor output voltage falls below the reference voltage.
→ The comparator output becomes high, which activates the relay driver circuit.

When the soil is wet, the sensor output voltage exceeds the reference voltage.
→ The comparator output becomes low, and the relay driver turns off.

Relay and Pump Operation:
The relay acts as a switch to control the water pump.

When the comparator output is high (dry soil), the relay energizes and turns on the pump, supplying water to the field.

When the soil becomes moist, the comparator output changes, de-energizing the relay and turning off the pump.

Automation:
This process continues automatically, ensuring that water is supplied only when needed — preventing both over-irrigation and under-irrigation.
