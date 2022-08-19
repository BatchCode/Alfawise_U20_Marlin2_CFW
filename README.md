# Alfawise_U20_Marlin2_CFW

# Prerequisite

1. Download any IDE (eg: VSCode)
2. Download Arduino IDE (might be optionnal)
3. Download Git SCM (might be optionnal)

# Setting up the dev environment

1. Open VSCode, browse to "extension" tab, then install `C/C++` and `PIO` (`Platform IO`)
2. Once PIO is installed, you will need to restart VSCode. This step CAN NOT be skipped.
3. Open Arduino IDE, press `CTRL+SHIFT+I` (or navigate to the "Tools" tab then click on "Library"), then install `U8glib` and `U8glib-HAL`

# Compiling the project

1. Open VSCode, then open the project's ROOT folder. PIO will then read the full program, you will know that because a notification will be shown on the total bottom in the middle of VSCode and disappear after the process is fully complete.
**Do not halt or stop that process as it is required in order to compile nor build the firmware.**
2. You are now able to compile/build the final program that will be used for the printer; in the total bottom of VSCode on the left, you will notice few icons (after the ⚠️), click on the " ✓ " arrow to start building, then wait for the process to fully finish.
**Do not halt or stop that process as it is required in order to compile nor build the firmware.**

# FYI
Marlin_2.0.X_Beta_Alfawise_Ux0-master appears to be working and compiling since all compilation bugs are now fixed