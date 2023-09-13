# SD Mapper/Megaram 512K para MSX version @jgilcas

Este cartucho desarrollado por Fabio Belavenuto  (https://github.com/fbelavenuto/msxsdmapper) permite disponer de un dispositivo de carga en el MSX a través de una microSD así como también asignar 512k de memoria RAM al ordenador.

Esta versión se ha modificado para disponer de un solo socket SD, donde su formato ya no es SD sino MicroSD. También se han cambiado las huellas de algunos componentes para facilitar la labor de soldadura.

Se incluye el esquema y los ficheros gerbers para fabricarlo.

If you like the project or want to support it, you can buy me a beer or a KO-FI :) 
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H51MPWG)

# Imagen

<img src="https://github.com/arananet/SdMapperMSXJGILCAS/blob/master/images/front.png?raw=true" width="700">

# Pinout

1-TCK
2-GND
3-TDO
4-VCC
5-TMS
6-NC
7-NC
8-NC
9-TDI
10-GND

<img src="https://github.com/arananet/SdMapperMSXJGILCAS/blob/master/images/pinout_nuevo.png?raw=true" width="700">

# Updates

13/09/2023: Añadido pinout de programación.
05/08/2017: Version inicial del PCB.

# License

https://ohwr.org/cernohl

Copyright (c) 2014 - Fabio Belavenuto

Copyright (c) 2017 - @Edu_Arana

# Lista de materiales

| Part          | Value                   | Package                        |
| ------------- | ----------------------- | ------------------------------ |      
|  C1           | 100n                    | C0805                          |
|  C2           | 100uf                   | C0805                          |
|  C3           | 100n                    | C0805                          |
|  C4           | 100n                    | C0805                          |
|  C5           | 100n                    | C0805                          |
|  C6           | 100n                    | C1206                          |
|  C7           | 100n                    | C1206                          |
|  D1           | Cart1                   | CHIP-LED0805                   |
|  IC1          | AM29F010E               | TSOP32                         |
|  IC2          | HM628512ASOP32          | SOP32                          |
|  IC3          | XC95144XL_TQ100         | XC-TQ100                       |
|  IC4          | LM1117-3V3              | SOT223                         |
|  JP1          | MSXCART1                | MSXCART                        |
|  JT1          |                         | PH5X2                          |
|  R1           | 4K7                     | R0805                          |
|  R3           | 330                     | R0805                          |
|  R8           | 4K7                     | R0805                          |
|  R9           | 4K7                     | R0805                          |
|  R10          | 4K7                     | R0805                          |
|  S1           | TL32YO                  | TL3XYO                         |
|  S2           | TL32YO                  | TL3XYO                         |
|  T1           | BC858                   | SOT23-BEC                      |
|  U1           | USD-SOCKETUSD           | USD-SOCKET-PP                  |
|  X1           | 25MHz                   | 7X5 OSCILLATOR                 |



