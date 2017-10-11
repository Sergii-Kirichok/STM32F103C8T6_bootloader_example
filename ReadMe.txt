Examle of bootloader and aplication program. 
This examples made by SMT32CubeMX with suport HAL library for Kail MDK AVR 5x and tested on STM32F103C8T6.

Whow to use:
-Flush smt32f103c8t6 with bootloader_uart project
-Flush the same stm32f103c8t6 with FirmWare_overBootloader project
-connet to stm32f103c8t6 any usb-usart device to the  USART1 pins (PA9 an PA10)
-setup your usb-usart speed 115200, 8,no,1
-run the stm32f103 (powered it)

After start stm32f103 should send you a message  "Firmware-1" and starts blink by led connected on pc13.


Fitmware 1 -  accept come digits and react on it. 
1 - blink will light 300ms
2 - blink will light 600ms
5 - will reboot STM32f103
8 - will jump to Firmware-2


Fitmware 1 -  accept come digits and react on it. 
1 - blink will light 600ms
2 - blink will light 1100ms
9 - will reboot STM32f103
