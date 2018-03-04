// Written for CIS170C Week 1 Homework
// This program tells the user how many slices can be made from a pizza with x diameter
// Written: 3/4/18

#include <iostream>
using namespace std;

int main() {
	
	float diameter;
	float numSlices;
	float area;
	float radius;
	
	cout << "Enter pizza diameter: ";
	cin >> diameter;
	
	radius = diameter / 2;
	area = radius * radius * 3.14159;
	numSlices = area / 14.125;
	
	int slicesRounded = (int)(numSlices);
  cout << slicesRounded << " slices";

	return 0;

}
