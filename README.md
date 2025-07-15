# TrafficLightControl_UART
STM32F446RE
ARM Cortex M4

Create two project file -> one with sender.c + all other files except receiver.c
                        -> one with receiver.c + all other files except sender.c
                        
In MCU_2(Receiver)
  PB0 -> RED_1
  PB1 -> YELLOW_1
  PB2 -> GREEN_1
  PB3 -> RED_2
  PB4 -> YELLOW_2
  PB5 -> GREEN_2
  PA6 -> LOAD_1
  PA7 -> LOAD_2

PA0 & PA1 is RX and TX of UART/USART will be in cross-connection in two MCU
