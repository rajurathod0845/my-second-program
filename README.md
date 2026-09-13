# my-second-program

#include <iostream>
using namespace std; // Allows us to use cout/cin without the std:: prefix

int main() {
    int num1, num2, sum;
    
    cout << "Enter two integers separated by a space: ";
    cin >> num1 >> num2;
    
    sum = num1 + num2;
    cout << "The sum is: " << sum << endl;
    
    return 0;
}
