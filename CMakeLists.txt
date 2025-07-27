cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "TCA0548.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino-esp32)

project(TCA0548)