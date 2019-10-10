cmake_minimum_required(VERSION 3.15)
project(ARMAssemblyEmulatorWithC)

set(CMAKE_CXX_STANDARD 14)

add_executable(ARMAssemblyEmulatorWithC
        Debug/src/ArmEmulator.o
        Debug/src/ArmSimulator.o
        Debug/src/Dummy.o
        Debug/ArmEmulator.exe
        Debug/ArmSimulator.exe
        src/ArmEmulator.c
        src/Compile_ArmEmulator.bat
        src/Dummy.c
        src/ReadMe.txt)
