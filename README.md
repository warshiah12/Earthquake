# Earthquake
Lecture 7 exercise 6
#include<iostream>
using namespace std;
int main()
{
	float magnitude;   //declaring variable 'magnitude' with datatype float
	cout << "What is the magnitude? " << endl;  //ask the user for magnitude
	cin >> magnitude; //user input is stored in variable 
	if (magnitude < 2.0)   //using else if statement to determine the magnitude input by user according to Richter scale
	{
		cout << "Micro" << endl;
	}
	else if (magnitude >= 2.0 && magnitude < 3.0)
	{
		cout << "Very Minor" << endl;
	}
	else if (magnitude >= 3.0 && magnitude < 4.0)
	{
		cout << "Minor" << endl;
	}
	else if (magnitude >= 4.0 && magnitude < 5.0)
	{
		cout << "Light" << endl;
	}
	else if (magnitude >= 5.0 && magnitude < 6.0)
	{
		cout << "Moderate" << endl;
	}
	else if (magnitude >= 6.0 && magnitude < 7.0)
	{
		cout << "Strong" << endl;
	}
	else if (magnitude >= 7.0 && magnitude < 8.0)
	{
		cout << "Major" << endl;
	}
	else if (magnitude >= 8.0 && magnitude < 10.0)
	{
		cout << "Great" << endl;
	}
	else if (magnitude >= 10)
	{
		cout << "Meteoric" << endl;
	}
	return 0;
}
