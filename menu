#include <stdio.h>
#include <windows.h>
#define MENU_LIMIT 10
void gotoxy(int x, int y) {    
    COORD coord;
    coord.X = x;
    coord.Y = y;
    SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}
main()
{
	int i,j,y_menu=MENU_LIMIT,konum2;
	int exit=0;
	char yon,select;
		/*The menu starts here*/
		printf("\n\n\t-------------------------------------------------------------\n");
		printf("\t-----------------------PROGRAM MENU--------------------------\n");
		printf("\t-------------------------------------------------------------\n");
		printf("\n\n\t\t\t\tWelcome\n");
		printf("\n\n\t\tPlease press any button to continue ...\n");
	while(1)
	{
		select=getch();
		system("cls");
		printf("\n\n\t-------------------------------------------------------------\n");
		printf("\t-----------------------PROGRAM MENU--------------------------\n");
		printf("\t-------------------------------------------------------------\n\n\n\n\n\n");
		printf("\t\t\tMenu Option #1\n");
		printf("\t\t\tMenu Option #2\n");
		printf("\t\t\tMenu Option #3\n");
		printf("\t\t\tExit\n");
		printf("\n\n\n\n\n\n\n\n\n\n\n\tw/W and s/S for movement, f/F for select");
		if(select=='w' || select=='W')
		{
			y_menu--;
			if(y_menu<MENU_LIMIT)
			{
				y_menu=MENU_LIMIT;
			}
		}
		if(select=='s' || select=='S')
		{
			y_menu++;
			if(y_menu>MENU_LIMIT+3)
			{
				y_menu=MENU_LIMIT+3;
			}
		}
		if(select=='f' || select=='F')
		{
			if(y_menu==10)
			{
				/*add your code  here for option one*/
				system("cls");
				printf("\n\n\n\n\n\t\t\tMenu option #1 has been selected");
				/*add your code  here for option one*/
			}
			else if(y_menu==11)
			{
				/*add your code  here for option two*/
				system("cls");
				printf("\n\n\n\n\n\t\t\tMenu option #2 has been selected");
				/*add your code  here for option two*/
			}
			else if(y_menu==12)
			{
				/*add your code  here for option three*/
				system("cls");
				printf("\n\n\n\n\n\t\t\tMenu option #3 has been selected");
				/*add your code  here for option three*/
			}
			if(y_menu==13)
			{
				/*If you add some other options for the menu you should remove this part to the end of the menu options*/
				exit=1;
				/*If you add some other options for the menu you should remove this part to the end of the menu options*/
			}
		}
		if(exit==1)
		{
			system("cls");
			printf("\n\n\n\n\n\t\t Exit Screen");
			printf("\n\t-------------------------------------------------------------\n");
			printf("\n\n\t\t User Exits The Program\n\n\t\t Please press a button to exit");
			printf("\n\n\t-------------------------------------------------------------\n");
			break;
		}
		gotoxy(20,y_menu);
		printf("%c",254);
	}
		/*The menu ends here*/
	
	getch();
}
