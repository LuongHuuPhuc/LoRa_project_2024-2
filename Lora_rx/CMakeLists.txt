cmake_minimum_required(VERSION 3.5)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)

set(EXTRA_COMPONENT_DIRS ${CMAKE_CURRENT_SOURCE_DIR}/../component #Lora.h
                         ${CMAKE_CURRENT_SOURCE_DIR}/../../Esp32MCU_jigaku/components/SSD1306
                         ${CMAKE_CURRENT_SOURCE_DIR}/../../I2C_SCAN
                         ${CMAKE_CURRENT_SOURCE_DIR}/../Lora_bitmap)
                         
project(Lora_rx)