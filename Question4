#include <iostream>
using namespace std;

double calculateSum() {
    int n;
    double sum_value = 0;
    cout << "Enter the value of n: ";
    cin >> n;
    if (n == 0) {
        return 0;
    }
    sum_value = calculateSum();
    sum_value += pow(-1, n + 1) / n;
    return sum_value;
}

int main() {
    double sum_value = calculateSum();
    cout << "The sum of the equation is: " << sum_value << endl;
    return 0;
}
