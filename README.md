#include <iostream>
#include <string>

using namespace std;

int main() {
    string binaryInput;
    
    cout << "Введите двоичное число:";
    cin >> binaryInput;
    
    int decimalNumber = stoi(binaryInput, nullptr, 2);
    
    cout << "Шестнадцатеричное число: " << hex << uppercase << decimalNumber<< endl;
    return 0;
}
