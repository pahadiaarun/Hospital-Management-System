# Hospital-Management-System
##MAIN PARTS OF THE CODE THAT NEED EXPLAINING
1) **#include<fstream.h>**: Used for the file stream which has capabilities of both “ofstream” and “ifstream” i.e., it can create files, write information to files, and read information from files.
2) **#include<conio.h>**: Used for functions like clrscr(),getch(),delay(),gotoxy() etc.
3) **#include<string>**: Used for functions like strcmp() etc.
4) The **ctime()** function converts the time value pointed to by time to local time in the form of a character string. A time value is usually obtained by a call to the time() function. The ctime() function uses a 24-hour clock format.
5) The time-related type used in the program is **time_t** is capable of representing the system time and date as an integer. It returns the current calendar time of the system in the number of seconds elapsed. If the system has no time .1 is returned.
6) **char *ctime(const time_t *time)**: returns a pointer to a string of the form day month year hours:minutes:seconds:year\n\0.
7) **windows.h**: It defines a very large number of Windows-specific functions that can be used in C.
8) **Sleep Function**: The **sleep ()** function causes the program or the process in which it is called, to suspend its execution temporarily for some time in seconds specified by the function parameter. Execution is suspended until the requested time is elapsed or a signal or an interrupt is delivered to the function.However, if the system has scheduled any other activity, then the suspension time may be longer.
9) **System Function**: Using **system()**, we can execute any command that can run on the terminal if the operating system allows. Like in this program we have used a system to provide an attractive background color to the output screen. So we used an alike system(“Color 5F”) in which Color is providing color to the output screen, the user 5 is to provide background color (range is from 0 to 9) and F (range is from A to F) provides the text color.
  ![image](https://user-images.githubusercontent.com/80753977/175810117-caa77eb3-e854-4709-8096-08557d69b0b7.png)
