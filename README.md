# Lab-22.20-
#include <iostream>
using namespace std;

/*  Initializing arrays
Instructions: Add code to display the value of each element from the numbers array.
Then, add another array named myArray that is initialized with the following values:
8.5, 9.4, 3.5, 3.6, 9.5. Also add code to display all the elements from the array myArray.*/

int main() {
 
  double numbers[] = {2.0, 5.9, 4.3};
  numbers[0] = 2.0;
  numbers[1] = 5.9;
  numbers[2] = 4.3;
  double myArray[] = {8.5, 9.4, 3.5, 3.6, 9.5};
  myArray[0] = 8.5;
  myArray[1] = 9.4;
  myArray[2] = 3.5;
  myArray[3] = 3.6;
  myArray[4] = 9.5;


cout << "The numbers are: " << endl;
cout << numbers[0] << endl;
cout << numbers[1] << endl;
cout << numbers[2] << endl;
cout << myArray[0] << endl;
cout << myArray[1] << endl;
cout << myArray[2] << endl;
cout << myArray[3] << endl;
cout << myArray[4] << endl;
}
