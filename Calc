#include<iostream>
using namespace std;
//Step 1: write your nfunction declaration*
float add(int x, int y);
float subtract(int x, int y);
float multiply(int x, int y);
float divide(int x, int y);
// the above functions have a *return type* of float, and two int *parameters*


int main() { // start of main
	int a, b, c; // varianble declaration
	cout << "enter two numbers" << endl;
	cin >> a;
	cin >> b; 
	cout << " press 1 for add, 2 for multiply, 3 for subtract, 4 for divide" << endl;
	cin >> c;
	//step 3: call the function
	if (c == 1)
		cout << add(a, b);  //a and b are the *arguments* of the function
	if (c == 2)
		cout << multiply(a, b);
	if (c == 3)
		cout << subtract(a, b);
	if (c == 4)
		cout << divide(a, b);
}// end of main-------------------------------------

// step write your *function definition*
float add(int x, int y) {
	cout << "Here is the sum of your two numbers: ";
	return x + y;

}
float multiply(int x, int y) {
	cout << "Here is the product of your two numbers: ";
	return x * y;
}
float divide(int x, int y) {
	cout << "Here is the quotient of your two numbers: ";
	return x / y;
}
float subtract(int x, int y) {
	cout << "Here is the difference of your two numbers: ";
	return x - y;
}
