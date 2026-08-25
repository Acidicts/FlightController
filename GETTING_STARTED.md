# Getting Started
** Should be PCBA due to small parts **

## Step 1: Modify the firmware to meet your needs
- Add and edit code within `/* USER CODE BEGIN Includes */` and `/* USER CODE END Includes */` in [`software/Core/Src/main.c`](software/Core/Src/main.c)

## Step 2: Install and Build with Make
- Click [here](MAKE.md)

## Step 3: Install the firmware
- Use STM32CubeProgrammer over ST-Link/SWD to flash `FlightController.bin`, from your build folder after using make, at address 0x08000000
- Hold BOOT button while powering it on
