# STM32-Implementations

Author: Kenneth Galindo

# Purpose:

The purpose of this project is to display a simple LED blink test using the STM32CubeIDE, in order to set pins and generate code necessary for the project to compile and run. Within this folder we will find the necessary files for the build utilizing a **Nucleo-F303RE development board**, video demonstration of intended results, any necessary code files, and steps taken to accomplish the project.

![image](https://user-images.githubusercontent.com/98668234/186807291-f08e0940-7c5b-42b0-a62e-a0bdcf092bd9.png)

# Procedures:

The initial step is to open your workspace needed for the project, create a new project, and name it accordingly.

After completing this step, we can then choose a board (in this case the Nucleo-F303RE development board) and finalize the project settings. From here, we can utilize any needed pins for the project. From default settings, all necessary pins are set and can therefor generate the code.

Once code is generated, we can create two lines of code in order to set a delay value (in ms) to have our LED blink at an according rate. In this instance, the code used can be seen below, which is a delay of 1000ms or 1s on and 1s off.

![image](https://user-images.githubusercontent.com/98668234/187007523-732ebde4-b00e-4eef-b2c6-6ee484d1a2ce.png)

Once the lines of code are inserted, we can build the project and **run as a STM32 C/C++ Application**. Here we can refer to the video for the implementation.



