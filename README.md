# Vibration_sensor_hardware

## Hardware components
1. Geophone
2. Amplifier: https://www.sparkfun.com/products/9816
3. Arduino board: https://www.sparkfun.com/products/13664

## Connection
![Hardware component connection.](/sensor_connection.pdf)

First, there are two wires from Geophone. One wire (wire1) is connected to the ground. Another wire (wire2) is connected to the input of the amplifier module.
Then, the amplifier module is connected with VCC and Ground from Arduino. 
Finally, the output signal of the amplifier is connected to the ADC pin of the Arduino board. 
The Arduino board digitalizes the ADC pin signal and sends data to the Raspberry pi/laptop via serial cable.
