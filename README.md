# SPI Test Project
## Objective
To Apply master SPI interface using STM32 board
- create API for SPI
-- spiBegin(uint8 *baudRate)
-- spiRead8(uint8 *data,uint8 byteSize,bool endTransmission)
-- spiWrite8(uint8 *data,uint8 byteSize,bool endTransmission)

## Methodology
1) Test API for master device (Arduino) and connected to slave spi (Arduino). The salve SPI later will be use to test STM32 board master device spi.
2) Use the API as template for API to be develop in STM32 IDE env
3) Develop master SPI in STM32
4) Test the master SPI with slave device (arduino) spi
