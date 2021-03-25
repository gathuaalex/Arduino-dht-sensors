# Arduino-dht-sensors

## components

- arduino uno
- DHT11 sensor
- relay (SRD-05VDC-SL-C)
- LED (to act as a fan)
- 12v motor replace pump


*How it works*

if temperatures are above 28.5degrees celcius and humidity above 50.5 degrees celcius
  - on the serial monitor 
    - display "HIGH TEMPERATURE FAN ON"
    - display "HUMIDITY NORMAL PUMP OFF"
  - on arduino 
    - activate fan (LED ON)
    - deactivate pump (relay )
  
