# 26Sep2021_Assignment
// Odd or Even
#include <iostream>
using namespace std;
int main()
{
	cout << "Please enter a number." << endl;
	int number;
	cin >> number;
	if (number % 2 == 0) {
		cout << number << " " << "is an even number." << endl;
	}
	else {
		cout << number << " " << "is an odd number." << endl;
	}
	return 0;
}
  
  
  ------------------------------------------------------
  
  
// Number Checker
#include <iostream>
using namespace std;
int main()
{
	int number;
	cout << "Please enter a number." << endl;
	cin >> number;
	if (number < 0) {
		cout << number << " " << "is a negative number." << endl;
	}
	else if (number > 0) {
		cout << number << " " << "is a positive number." << endl;
	}
	else {
		cout << number << " " << "is a zero." << endl;
	}
	return 0;
}
  --------------------------------------------------------------------------------
  
  // Profit or Loss
  #include <iostream>
using namespace std;
int main()
{
	cout << "How much is the box of pens?" << endl;
	double pen;
	cin >> pen;
	cout << "Is there a sale?" << endl;
	string sale;
	cin >> sale;
	if (sale == "yes") {
		cout << "How much is the sale?" << endl;
		double Sale;
		cin >> Sale;
		cout << "I just saved " << pen - Sale << " " << "Aed!";
	}
	else {
		cout << "Oh alright! Well you just gained " << pen << " " << "Aed." << endl;
	}
	return 0;
}
  
  
  
  
  --------------------------------------------------------------------------------
  
  
  // Name that Shape
  #include <iostream>
using namespace std;
int main()
{
	cout << "Hello! I can tell you what shape you're thinking. \n";
	cout << "Please enter a number between 3 and 10. \n";
	int number;
	cin >> number;
	if (number == 3) {
		cout << "You are thinking of a triangle." << endl;
	}
	else if (number == 4) {
		cout << "Is it all equal sides?" << endl;
		string sides;
		cin >> sides;
		if (sides == "yes") {
			cout << "You are thinking of a square." << endl;
		}
		else {
			cout << "You are thinking of a rectangle." << endl;
		}
	}
	else if (number == 5) {
		cout << "You are thinking of a pentagon." << endl;
	}
	else if (number == 6) {
		cout << "You are thinking of a hexagon." << endl;
	}
	else if (number == 7) {
		cout << "You are thinking of a heptagon." << endl;
	}
	else if (number == 8) {
		cout << "You are thinking of a octagon." << endl;
	}
	else if (number == 9) {
		cout << "You are thinking of a nonagon." << endl;
	}
	else if (number == 10) {
		cout << "You are thinking of a decagon." << endl;
	}
	else {
		cout << "Please enter a number between 3 and 10. \n";
	}
	return 0;
}
  
  
  
  
  
  
  
