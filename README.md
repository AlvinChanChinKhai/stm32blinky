# stm32blinky
Task: Blink the STM32F4 on board LED repeatedly after each second.

Group Name: Savvy Falcon

Group Members
- 
  1. Alvin Chan Chin Khai
  2. Beh Jun Long

Project Execution
- 
1.	Download and install the STM32CubeIDE software from https://www.st.com/en/development-tools/stm32cubeide.html
2.	Launch the software and click on File -> New -> STM32 Project in the selection tab to start a new project.
3.  Click on “Board selector” tab and enter the name of the of the board to be used in the commercial part number section, which in this case is “NUCLEO-F411RE”. Then,     search for the board we are using and click next.
4.	After that, key in the project name and leave everything by default and click “Finish”. Then, a “Initialize all peripherals with their default Mode?” message will     pop out, click “Yes” to proceed.
5.	Take note that the on-board green led is located at the pin “PA5”. Left click on it and choose GPIO_Output.
6.	![image](https://user-images.githubusercontent.com/118992897/203946373-e902a81c-0de9-414e-b00d-5cae9230b4a4.png)

 
6.	Click on the “Project” tab and click on the generate code to generate the code or this project.
7.	Inside the generated C code, look for the while loop and type in the code to blink the LED. 
 

8.	Click on the hammer button    to compile and debug the project and make sure there are no error in the code.
9.	Next, click on the run button   to upload the code to STM32 board. A pop window will show up, leave everything as default and click “Ok”.
10.	Wait for this message to show inside the console window to indicate the code is successfully uploaded to the board. After a short while, the STM32 board LED should     be start blinking.
 
	


Youtube link: 
- 
  - ?

View the attached document "Step 1- Validate lab environment.docx" for steps to blink the LED.

References: 
  - https://www.youtube.com/watch?v=oAwZ0cjlmN8&t=846s&ab_channel=MicroPetabyNizarMohideen
