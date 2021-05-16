# Birdhouse Peeper

A system to monitor inside a birdhouse.




python3
>>> import smbus
>>> b = smbus.SMBus(1)
>>> b.read_i2c_block_data(0x23, 0x20)
[0, 4, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255, 255]
