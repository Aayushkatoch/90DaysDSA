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

  
DAY 2:
#include <iostream>
using namespace std;

int main() {

  int i, n;
  bool is_prime = true;

  cout << "Enter a positive integer: ";
  cin >> n;

  if (n == 0 || n == 1) {
    is_prime = false;
  }

  for (i = 2; i <= n/2; ++i) {
    if (n % i == 0) {
      is_prime = false;
      break;
    }
  }

  if (is_prime)
    cout << n << " is a prime number";
  else
    cout << n << " is not a prime number";

  return 0;
}  


DAY 3:
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter The no of day of week:  ";
    cin >> n;

    switch (n) {
        case 1:
            cout << "Monday";
            break;
        case 2:
            cout << "Tuesday";
            break;
        case 3:
            cout << "Wednesday";
            break;
        case 4:
            cout << "Thursday";
            break;
            case 5:
            cout << "Friday";
            break;
            case 6:
            cout << "Saturday";
            break;
            case 7:
            cout << "Sunday";
            break;
        default:
            cout << "Error! The number is not correct";
            break;
    }

    return 0;
}
