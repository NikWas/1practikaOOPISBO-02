#include <iostream>
#include <cstdlib>
#include <locale.h>
using namespace std;

int main()
{
    setlocale(LC_ALL, "russian");
    string name;
    float num1, num2, res=0;
    char pl;
    cout << "Name: ";
    cin >> name;
    cout << "Hello, " << name << "!" << endl;
    cout << "Введитееееееееееее: ";
    cin >> num1;
    cout << "Enter second number: ";
    cin >> num2;
    cout << "+,-,*,-? ";
    cin >> pl;
    switch(pl)
    {
        case '+':
            res = num1 + num2;
            break;
        case '-':
            res = num1 - num2;
            break;
        case '*':
            res = num1 * num2;
            break;
        case '/':
            res = num1 / num2;
            break;
        default:
            cout << "Error" << endl;
            break;
    }
    cout << "The result is " << res;
    system ("pause");
    return 0;
}

