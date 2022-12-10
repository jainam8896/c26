# c26#include<iostream.h>

#include<conio.h>

#include<iomanip.h>

ostream &rpad(ostream &stream)

{

	stream.setf(ios::left);

	stream<<setw(20)<<setfill(' ');

	return stream;

}

int main()

{

	clrscr();

	cout<<10<<" "<<rpad<<10<<20<<endl;

	cout<<10<<" "<<rpad<<100000<<20;

	getch();

	return 0;																																																																																																																;

}
