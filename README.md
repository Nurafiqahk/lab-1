# lab-1
week 1-exercise 1 
// Project1.cpp : Exercise 1 

#include <iostream>
using namespace std;

void fun();
int main()
{
    cout << "University : Universiti Teknikal Malaysia, Melaka\n";
	cout << "Faculty    : FTMK\n";
	cout << "Programme  : Artificial Intelligence\n";
	cout << "\nMy name is Nurafiqah binti khosni. I am from Pahang.\n";

	cout << "\n************************************\n";
	cout << "**************  UTEM  **************\n";
	cout << "************************************\n";
	cout << "Press any key to continue . . .\n";

	cout << "\n10\n";
	cout << " 9\n";
	cout << " 8\n";
	cout << " 7            *\n";
	cout << " 6 *\n";
	cout << " 5                    *\n";
	cout << " 4   *\n";
	cout << " 3               *\n";
	cout << " 2     *\n";
	cout << " 1 *\n"; 
	cout << " 0 1 2 3 4 5 6 7 8 9 10\n";
	cout << "\n\nPress any key to continue . . .\n";

	return 0;
}
// Project4.cpp : This is my second try on Visual. Practicing on example 1 (ms 36)

#include <iostream>
using namespace std;
#define MILE_TO_KM 1.609

int main()
{
	double miles, km;

	cout << "Enter the distance in mile:"<<endl;
	cin >> miles;
	km = miles * MILE_TO_KM;
	cout << "\nThat equals " << km << " kilometers " << endl;
	return 0;
}
 
