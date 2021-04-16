# Vaja10-SPI-LIS3DSH-STM32F4-
ODGOVORI NA VRAŠANJA:
- SCK:
Serial Clock

- MISO:
MasterInput, Slave Output

- MOSI:
Master Output, Slave Input

- SS:
slave select

- SDI:
Serial Data Input

- SDO:
Serial Data Output

- CS:
Chip select


- V zavihku Pinout izberite SPI1 in izberite Full-Duplex Master. Kateri pini se obarvajo zeleno?
PA5, PA6 in PA7.

- V gumbu GPIO aktiviramo salve select CS_I2C/SPI na High GPIO Output level. Kateri pin je to? 
PE3

- V gumbu SPI1 nastavimo prescaler na takšno vrednost, da bo hitrost prenosa 1 MBits/s (baud rate). Koliko je vrednost skaliranja?
Vstavil sem vrednost 16, a Baud Rate sem dobil 5.25 MBits/s. 

- TABELA (meritve x osi):
ODR3=0	ODR2=0	ODR1=0	ODR0=1	BDU=0	Zen=0	Yen=0	Xen=1

KOMENTAR:
Koda sicer nima napak saj proram izpise 0 errors in 0 bugs, a ga nisem mogel naložiti na STM zaradi težav s programsko opremo (Program zahteva novejšo verzijo, a ko jo hočem prenesti ne pokaže novejše različice).
