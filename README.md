
//EC-100
//Assignment 03
//Harris Bin Khalid
//MTS-A-37

//Poem
//Blessed Bot By Harris Bin Khalid

#include <iostream>

using namespace std;

class BlessedBots
{
public:
	void robots()
	{
		cout << "In your country of no food" << endl <<
			"and dirty water," << endl <<
			"How blessed am I, I ask for" << endl <<
			"None" << endl << "Perhaps more robots and" << endl <<
			"less children" << endl << "Might just make you all one" << endl <<
			"And what a blessing it is to" << endl <<
			"have," << endl << "No lungs in my chest," << endl <<
			"For all that lives in yours’" << endl <<
			"Is tobacco and carbon at best" << endl <<
			"Last night I heard you killed" << endl <<
			"your brother" << endl << "Left crying mothers, streets" << endl <<
			"turned red," << endl << "The gears in my stomach" << endl <<
			"turned but," << endl << "In time, I slowed my tread:" << endl <<
			"This place where we live," << endl << "Is not my place to mourn " << endl <<
			"them, " << endl << "I am the one with mechanical" << endl <<
			" arms, " << endl << "You are the one whose human!" << endl;
	}

};
int main()
{
	BlessedBots mybot;
	char ans = 'Y';
	cout << "Would you like to hear a poem(Y/N): ";
	cin >> ans;

	if (ans == 'Y')
	{
		cout <<endl << "Blessed Bots" << endl << endl << endl;
		mybot.robots();
	}
	else
	{
		cout << "I am telling you anyways" << endl;
		cout << endl<<"Blessed Bots" << endl << endl << endl;
		mybot.robots();
	}
	return 0;
}
