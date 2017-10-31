#include <iostream>
#include <cstring>
#include <sstream>

using namespace std;

bool palindrome(string word)
{
	int Length = word.length();
	for (int i = 0; i < Length / 2; i++)
	{
		if (word[i] != word[Length - i - 1])
			return false;
	}
	return true;
}

int main()
{
	string str;
	cout << "Enter the word: ";
	getline(cin, str);
	cout << "Result: \n";
	if (palindrome(str))
		cout << "1 \n";
	else
		cout << "0 \n";
	return 0;
}
