# Assesment-

#include<iostream>
using namespace std;
int main() {
	string name;
	int x;
	cout << "entrer full name:" << endl;
	cin >> name;
	cout << "enter the number" << endl;
	cin >> x;

	int i = x - 1;

	do {
		x = x * i;
		i=i;
	} while (i > 0);

	cout << "factorial is: " << x << endl;
	return 0;

}
