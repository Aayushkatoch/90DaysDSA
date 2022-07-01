# 90DaysDSA


DAY 1:
#include <iostream>
using namespace std;

int main() {

  int number;

  cout << "Enter an integer: ";
  cin >> number;

  if (number %2== 0) {
    cout << "Even." << number << endl;
  }

  else cout << "Odd.";

  return 0;
}
