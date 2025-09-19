#Heater Control System
Name- Swaraj Wanjale
Department- Computer Engineering
Roll no.- 52
Division - CE2
1. Research 
In this activity, we will simulate the control of a heater using a C program. The goal of this program is to create a simple on/off control system, where the user can either turn the heater on or off based on their input. The program will take an input as either 0 or 1
0 to turn the heater OFF
1 to turn the heater ON
Any other input should be treated as invalid.

2. Analysis
To design a control system that allows a user to switch a heater ON or OFF by entering a simple command (0 for OFF, 1 for ON). 

3. Ideate
The concept for the heater control system was developed by focusing on creating a user-friendly and straightforward method to manage the heater’s power state. The purpose of this activity is to simulate a real-world system specifically, an electrical switch that turns a heater on and off.
The core idea of the Heater Control System revolves around binary control—using 0 to represent a state (heater off) and 1 to represent another state (heater on).


4. Build 
#include <stdio.h>
int main(){
    int a;
    printf("Enter 0 to turn off the heataer or 1 to turn on the heater \n");
    scanf("%d",&a);
    if(a==1){
        printf("Heater is turned on");
    }
    else {
        printf("Heater is turned off");
    }
    return 0;
}

5. Testing
To turn the heater off the user inputs the value as 0.
OUTPUT 
Enter 0 to turn off the heater or 1 to turn on the heater 
0
Heater is turned off
To turn the heater on the user inputs the value as 1.
OUTPUT
Enter 0 to turn off the heater or 1 to turn on the heater 
1
Heater is turned on
6. Implementation
The project is published on google for easy access to the code.
Link: https://github.com/Swaraj-web27/Heater-control-system/blob/main/README.md
7. Conclusion
In this activity, we successfully developed a simple heater control system in C that takes user input to turn the heater on or off. By taking 0 or 1 as input  to switch off or on the heater. The project also highlights the importance of input validation and user friendly messaging software development.
