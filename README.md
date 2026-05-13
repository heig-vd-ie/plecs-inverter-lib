# PLECS Library by HEIG-VD/IE
This PLECS standalone library was created to add different components that are not part (yet) of the standard PLECS library.  
## Content of the library 
  
* **Inverter**
    - Grid forming inverter (direct voltage control with protection)
    - Grid following inverter (with grid code protections included)
    - Power part of an inverter with an LCL filter
* **Grid components**
    - Multiphase load with different configuration 
    - Pi-section lines
    - Ideal grid
* **Transformations**
    - Power calculation
    - abc -> dq0 and vice-versa
    - Symetrical components
    - Monophasors
    - And many more...
* **Miscellaneous**
    - Variable saturation
    - Impulse generator
    - Turn on/off delay
    - Rotating field direction detector
    - And many more...
* **Complex operators**
    - Product
    - Division
    - Conjugate
    - Complex power
    - And many more...
* **Type conversion**
    - uint8 to byte
    - byte to uint8
    - uint16 to 16 bits
    - 16 bits to uint16
    - SPI pack : pack float32 to send over SPI
    - SPI unpack : unpack message sent over SPI to float32