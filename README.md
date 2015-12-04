# Yotta project to play with Mbed OS on the STM32F4-Discovery Board

# Requirements
 - Yotta
 - Cmake
 - Ninja
 - Arm toolchain

# Usage
Build with `yotta build`  
Flash with `./flash.sh`

# Tricks

## Compiler error, missing <cstdtypes>

export CPATH=${TOOLDIR}/c++/4.9.3/:${TOOLDIR}/include/:${TOOLDIR}/include/c++/4.9.3/arm-none-eabi/armv7-m/