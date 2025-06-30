# STM32F411 Nucleo: Interrupt-Driven LED Toggle  

## Description  
Toggles the onboard LED (PA5) via EXTI interrupt when the user button (PC13) is pressed.  

## Key Features  
- **Interrupt-driven**: Button triggers EXTI interrupt on rising edge  
- **Hardware**: STM32F411RE Nucleo (LED=PA5, Button=PC13)  
- **Config**:  
  - Clock: HSI (16MHz, no PLL)  
  - GPIO:  
    - PC13: Input with rising-edge interrupt  
    - PA5: Push-pull output  

## Usage  
1. Flash to STM32F411RE Nucleo  
2. Press the blue user button (B1) to toggle the green LED (LD2)  

## Dependencies  
- STM32Cube HAL  
- Generated with STM32CubeIDE  / STM32CubeMX
