# uREU64 design

## Basic Blocks

### electrical conversion
The Commodore voltage is 5 V the cartridge logic runs 3.3 V By means of 74xx245 3-state dual supply trancievers we can both level translate and read, write and disconnect from the cartrigde port. probably 5 or 6 ic's are needed.

### logic
The idea is to do almost all of the logic in **Firmware** on a relatively cheap microcontroller. 

Options from Microchip/Atmel are
* ATSAM4S(2|4|8|16)C Cortex-M4 120 MHz SRAM only
  - 100 pin package does not seem to have enough pins to comfortly asign all signals (and external SRAM)
* ATSAMS70Q(19|20|21) Cortex-M7 300 MHz SRAM/SDRAM
* ...


### memory
One option is to use relatively simple SRAM to provide the large memory pool. This would most likely meet the timing requirements needed.

Dependant on the microcontroller there is the option to use cheaper (per byte) DRAM. 

### TODO
* investigate DRAM cost-benefit
