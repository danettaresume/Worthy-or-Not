#include <iostream>
int main() {
    for (int i = 1; i <= 100; i++) {
        if (i % 3 == 0 && i % 5 == 0) {
            std::cout << "Worthy!\n";
        } else if (i % 3 == 0) {
            std::cout << "Lift\n";
        } else if (i % 5 == 0) {
            std::cout << "Strike\n";
        } else {
            std::cout << i << "\n";
        }
    }
    return 0;
}
