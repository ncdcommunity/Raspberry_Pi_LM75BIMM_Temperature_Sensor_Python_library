[![LM75BIMM](LM75BIMM_I2C.png)](https://store.ncd.io/product/lm75bimm-temperature-sensor-%C2%B12c-9-bit-with-3-address-lines-i2c-mini-module/).

# LM75BIMM

The LM75 temperature sensor includes a delta-sigma analog-to-digital converter and a digital over- temperature detector.The open-drain over-temperature output (OS) sinks current when the programmable temperature limit is exceeded.
This Device is available from www.ncd.io

[SKU: LM75BIMM]

(https://store.ncd.io/product/lm75bimm-temperature-sensor-%C2%B12c-9-bit-with-3-address-lines-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface LM75BIMM temperature sensor With Raspberry Pi :

1. <a href="https://store.ncd.io/product/lm75bimm-temperature-sensor-%C2%B12c-9-bit-with-3-address-lines-i2c-mini-module/">LM75BIMM temperature sensor</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>

3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python

Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python LM75BIMM.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
