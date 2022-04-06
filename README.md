The purpose of this program is to measure the temperature and Humidity from sensor (DHT11) and display LCD and send the to another point by LoRa, The Lora module is RFM95W-915S2 and is connect to ESP 32 

The regulator that is using is LM25965 (Convesor Step Down)  much more efficient than 7805 to use with battery.

The circuit is powered by a battery that is recharged by a 12VDC source, this power circuit has a voltage regulator that limits to 5V and a battery recharge module ( TP 4056) that supply voltage to ESP 32 and avoid reverse current.

