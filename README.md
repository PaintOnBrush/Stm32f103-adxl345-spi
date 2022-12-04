# Stm32f103-adxl345-spi
adxl345 spi interface to stm32f103 using stm32cubeide hal

using the blue pill board and a adxl345

#spi connection:  
stm32 <-> adxl345  
-------------------  
PA4 <-> CS  
PA5 <-> SCL  
PA6 <-> SDO   
PA7 <-> SDA  
gnd <-> gnd  
3.3v <-> 3.3v  

#UART connection:  
stm32 <-> UART  
-------------------   
PA9(TX) <-> RX  
PA10(RX) <-> TX  
gnd <-> gnd  
3.3v <-> 3.3v  

stm32cubeide 1.11.0 project

