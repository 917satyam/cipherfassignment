#include <iostream>
#include <string>


int stringLength(const std::string &str) {
    int length = 0;
    for (char ch : str) {
        length++;
    }
    return length;
}

int main() {
    std::string str1 = "Hello, World!";
    std::string str2 = "C++ programming!";
    std::string str3 = "Test string";
    std::cout << "Length of '" << str1 << "' is: " << stringLength(str1) << std::endl;
    std::cout << "Length of '" << str2 << "' is: " << stringLength(str2) << std::endl;
    std::cout << "Length of '" << str3 << "' is: " << stringLength(str3) << std::endl;
    return 0;
}
