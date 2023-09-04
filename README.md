# Basic_GPIO_Driver
This repo contains a little project of a basic GPIO driver to use a GPIO as an external interrupt using STM32 Nucleo Board

The system description of the project is the next:
1.- We have a button connected to the PIN B0, this pin is configurated as an input and it will trigger an external interrupt
2.- The LED on the Nucleo board will be ON, when the button is pressed it will trigger an external interrupt and inside the interrupt handler the LED will be turned OFF.
