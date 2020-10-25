#include <iostream>
#include <cmath>

using std::cin;
using std::cout;
using namespace std;

int a, b, choice;
void no();
int main()
{
	cout << "[1 Addition]\n";
	cout << "[2 Subtraction]\n";
	cout << "[3 Divition]\n";
	cout << "[4 Multiplication]\n";

	cout << "\nEnter a Number: ";
	cin >> choice;

	switch (choice)
	{
	case 1:
	{
		cout << "Enter Firstnumber:";
		cin >> a;
		cout << "Enter Secondnumber:";
		cin >> b;

		choice = a + b;
		cout << "\nSum = " << choice;

		cout << "\n\nwoud you like go in operator again?\n 1[yes] 2[no]\n";
		cin >> choice;
		system("cls");
		if (choice == 1)
		{
			main();
		}
		else if (choice == 2)
		{
			no();
		}
		break;
	}
	case 2:
	{
		cout << "Enter Firstnumber:";
		cin >> a;
		cout << "Enter Secondnumber:";
		cin >> b;

		choice = a - b;
		cout << "\nSubtract = " << choice;

		cout << "\n\n you like go in operator again? 1[yes] 2[no]\n";
		cin >> choice;
		system("cls");
		if (choice == 1)
		{
			main();
		}
		else if (choice == 2)
		{
			no();
		}
		break;
	}
	case 3:
	{
		cout << "Enter Firstnumber:";
		cin >> a;
		cout << "Enter Secondnumber:";
		cin>> b;
		if (choice == 1)
		{
			main();
		}

		choice = a/b;
		cout << "\nDivide = " << choice;

		cout << "\n\nwoud you like go in operator again? 1[yes] 2[no]\n";
		cin >> choice;
		system("cls");

		if (choice == 1)
		{
			main();
		}
		else if (choice == 2)
		{
			no();
		}
		break;
	}
	case 4:
	{
		cout << "Enter Firstnumber:";
		cin >> a;
		cout << "Enter Secondnumber:";
		cin >> b;

		choice = a * b;
		cout << "\nMultiply = " << choice;

		cout << "\n\nwoud you like go in operator again? 1[Yes] 2[no]\n";
		cin >> choice;
		system("cls");
		if (choice == 1)
		{
			main();
		}
		else if (choice== 2)
		{
			no();
		}
		break;
	}
	}
}
void no()
{
	cout << "thankyou for using me.";
}
