# Experiment-2
## Aim-
To study and implement C++ program(Data types)
## Theory-
Understanding the size of various data types is crucial for memory management and optimization in programming. Different data types (e.g., int,short int,long int,float, double,long double,bool,char,auto,register) occupy different amounts of memory. and checking of size of some data types given by user.
### Int datatype-
In Python, the int type can represent arbitrarily large numbers, limited only by the amount of available memory, as Python automatically handles larger integers with its built-in int type.The int type is fundamental in programming for performing arithmetic operations, loops, indexing arrays, and more.
### Float datatype-
The float data type is used to represent real numbers with fractional parts, allowing for the representation of both whole and decimal numbers.Floats support arithmetic operations like addition, subtraction, multiplication, and division.Floats are widely used in scientific calculations, graphics, simulations, and any application requiring real-number arithmetic.
### Double datatype-
The double data type is used to represent double-precision floating-point numbers. It provides greater precision and a larger range than the float data type. Double-precision floating-point format is also based on the IEEE 754 standard, typically using 64 bits.
### Char datatype-
The char data type is used to represent single characters.The char data type is fundamental for text processing, file I/O operations, and any context where individual characters need to be manipulated or analyzed.
### Auto datatype-
The auto keyword is a feature in C++ (introduced in C++11) that allows the compiler to automatically deduce the type of a variable from its initializer.The auto keyword is a powerful tool in C++ that can lead to cleaner, more maintainable code when used judiciously.
### Register datatype-
The register keyword in C and C++ is used to suggest to the compiler that a particular variable should be stored in a CPU register, if possible, for faster access.
## Code-
1)-
```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;
int main(){
    cout<< "Size of intergers is "<< sizeof(int)<< " bytes"<< endl;
    cout<< "Size of float is "<< sizeof(float)<< " bytes"<< endl;
    cout<< "Size of strings is "<< sizeof(string)<< " bytes"<< endl;
    cout<< "Size of character is "<< sizeof(char)<< " bytes"<< endl;
    cout<< "Size of double is "<< sizeof(double)<< " bytes"<< endl;
    cout<< "Size of long is "<< sizeof(long)<< " bytes"<< endl;
    cout<< "Size of boolean is "<< sizeof(bool)<< " bytes"<< endl;
    return 0;
}
```
### Output-
![E179C4A0-0105-4BB8-B59C-B1A2D6C63000](https://github.com/user-attachments/assets/6016ce57-1249-4598-b367-2ff884193e2a)

2)-
```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;

void staticExample(){
    //int z=0;
    static int z=0;
    z++;
    cout<< "The value of z is: "<<z<<endl;
}

int main(){
    staticExample();
    staticExample();
    staticExample();    
    return 0;
}
```
### Output-
![Image 12-08-24 at 3 49 PM](https://github.com/user-attachments/assets/b309bcc9-80e7-4145-84d2-88abadedc878)
## Conclusion-
This program helps in understanding how much memory is allocated for different data types, which is important for writing efficient and optimized code.



![Image 12-08-24 at 3 49 PM](https://github.com/user-attachments/assets/a4efcd0f-3b24-412f-8264-91347d8b2f5b)

