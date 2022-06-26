# Hospital-Management-System
## MAIN PARTS OF THE CODE THAT NEED EXPLAINING
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

  ## LOGIC OF THE PROGRAM:
  Hospital Management System is based on the concept of recording patient records and their diagnosis information. Before stepping into the main system a user has to pass through a login system to get access, then only the user can add a new patient record, diagnosis information and check the full history of the patient. This mini project contains limited features, but the essential one. 
  
Talking about the features of the Hospital Management System, after logging in as a user he/she can add new patient records, diagnosis information, check patient information, and view information about the hospital. To delete a record, the user has to delete the file from the project folder as this project focuses on adding and retrieving files. While adding a patient record, he/she has to provide the details which include the name of the patient, address, contact number, age, sex, blood group, disease name, and patient id number. Similarly, in adding diagnosis information of a particular patient then he/she has to select the respective patient’s file and provide symptoms, Diagnosis, Medicines, ask admission, and ward type. The user can view the patient’s history easily as which displays every detail of the patient. 
  
There is a list file as well as the patient file which records the diseases of the patients are suffering from and the treatment provided with the bill with date and time. We also used the common thing used in all computers to enter username and password which will be only accessible to the one on the job of handling the patient’s record and we also inserted a for loop to enter the password in the form of “*” so that the password can be secured. 
  
## FLOW CHART
  The flowcharts have been presented for:
  - **LOGIN PAGE/HOMEPAGE**
  ![image](https://user-images.githubusercontent.com/80753977/175810240-030df675-93bf-4e7a-a8ed-0fed2ebb445a.png)
  - **DEPARTMENT CHOICES**
  ![image](https://user-images.githubusercontent.com/80753977/175810288-94ae63f8-1c9a-4a77-9781-38be0fe22872.png)
  
  
  ## OUTPUT:
  
 Front Page: 
•	ADMIN LOGIN PAGE 
 ![image](https://user-images.githubusercontent.com/80753977/175810372-167d2596-b0b6-4a03-9ca4-e6e40cbcd6bc.png)
 
•	HOMEPAGE 
 ![image](https://user-images.githubusercontent.com/80753977/175810380-8c51b90a-5a99-4b2a-8d9e-e03b3e55aa2a.png)
 
 https://github.com/pahadiaarun/Hospital-Management-System/blob/main/Output/Output.pdf
