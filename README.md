# PF-TASK
#include <iostream>
using namespace std;

int main() {
    float num1, num2, num3;
    cout << "Enter three numbers: ";
    cin >> num1 >> num2 >> num3;
     if (num1 == num2 && num2 == num3) {
        cout << "The numbers are equal" << endl;
    } else {
        cout << "The numbers are not equal" << endl;
    }

    return 0;
}
