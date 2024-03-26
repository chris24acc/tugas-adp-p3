#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    for (int i = 1; i <= 80; i++) {
        if (i % 4 == 0) {
            cout << "   DOR "<<"    ";
            if (i % 8 == 0) {
                cout << endl;
            }
            continue;
        }
        if (i < 10) {
            cout << setw(3) << i << "      ";
        } else {
            cout << setw(4) << i << "     ";
        }
    }
    return 0;
}
