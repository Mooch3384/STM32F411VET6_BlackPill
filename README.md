# STM32F411VET6 BlackPill Projects 🚀

This repository contains a collection of firmware projects and peripheral examples for the **STM32F411VET6 (BlackPill)** development board. The goal is to provide clean, well-documented code for learning and rapid prototyping.

## 🛠 Hardware Specifications
- **MCU:** STM32F411VET6 (Arm® Cortex®-M4 with FPU)
- **Core Speed:** Up to 100 MHz
- **Memory:** 512 KB Flash, 128 KB SRAM
- **Connectivity:** USB-C, SPI, I2C, UART, ADC, etc.

## 💻 Software & Tools
- **IDE:** [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html) (or Keil uVision/VS Code + PlatformIO)
- **Library:** STM32Cube HAL (Hardware Abstraction Layer) or LL (Low-Layer)
- **Toolchain:** GNU Arm Embedded Toolchain

## 📂 Repository Structure
Each folder represents a specific feature or peripheral:
- `GPIO_Blinky/` - Simple LED toggle
- `UART_Printf/` - Serial communication and retargeting printf
- `ADC_DMA/` - Multi-channel analog to digital conversion using DMA
- `I2C_OLED/` - Interfacing with an SSD1306 OLED display
- `USB_Device_HID/` - Configuring the board as a Mouse/Keyboard

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/STM32F411VET6_BlackPill.git
