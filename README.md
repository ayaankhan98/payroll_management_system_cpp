# payroll_management_system_cpp
A university payroll system which generates the payslip of the employee of the university (Written in Borland C++)

## Header Files Used 

1.	#include<iostream.h>  
             For basic input and output functioning of program.
2.	#include<conio.h>
 ###         Functions Used
                a.	clrscr()         clears text mode window
                b.	clreol()         clears to end of line in text window
                c.	cprintf()       sends formatted output to the text window on the screen
                d.	getch()         it puts a character in memory but does not display on output screen
                e.	getche()       it puts a character in memory and display on the output screen
                f.	gotoxy()       place cursor in the text window
                g.	textcolor()   selects a new character color in text mode

###          Constants used
                 a.       BLINK           to make the text blink in text mode

3.      #include<dos.h>
###             Functions Used
                a.	delay()          suspends execution for interval (milliseconds)

4.    #include<process.h>
###             Functions used
                a.	exit()           terminates the program

5.  #include<ctype.h>
###             Functions Used
                a.	isspace()           to check a space
                b.	isupper()          to convert a character into upper case
                c.	islower()           to convert a character into lower case
                d.	isdigit()             to check a digit
                e.	isalpha()	to  check a alphabet
                f.	toascii()	to convert a character into its ASCII value

6. #include<fstream.h>
###             Functions Used
                a.	seekp()       to place cursor in a data file during output mode
                b.	seekg()	to place cursor in a data file during input mode
                c.	tellg()	to return the cursor position from a data file during input mode
                d.	eof()	to check the ending of a data file

## Classes Used

1.	class admin	               class used for administration login purpose
###         Public Functions
            a.	void login()       for login purpose (password and username)
2.	class employee             class contain information about the employees such as name , address ,        phone                                  number , gender , marital status , designation , employee code
###         Public Functions
            i.	void registration()        new employee registration
            ii.	void reg_sucess()	stores data of employee if registration is successful
            iii.	void reg_code()		assign code for a new employee
            iv.	void modify()		modify a existing employee record
            v.	void show_employee() 		show record of a particular employee on the basis of     employee code
            vi.	void about()		contain  information about developers
            vii.	void pay_slip()		prints the pay slip of a employee
    
## Data Files Used
1.	edBase.txt          data file stores employee code
2.	dBase.txt	data file stores employee data


## User Defined Functions

1.	void f_page()              defines the front page
2.	void design()               design border for each page		
3.	void error()                 display a error message
4.	void menu()                generate main menu of program
5.	void loading()             show a loading message
6.	int date(int,int,int)    check date input by user is correct or incorrect

## Arrays Used 

1.	name[30]           contains employee  name
2.	address[100]    contains employee address
3.	phone[10]           contains employee phone number
4.	pass2[]                contains correct password required for login
5.	pass[]                 contains user password input  

## ASCII VALUES USED (for special purpose)

1.	Backspace    8
2.	Enter        13
3.	Esc          27








