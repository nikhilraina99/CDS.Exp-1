# CDS.Exp-1
# Experiment-1
## Aim - 
Downloading and installing of vs code,Hello world and calculator program.

## Theory - 
we study about downloading and installing of vs code and the start doing programs in it.

These programs introduce fundamental concepts in C++ programming:

Hello World: Demonstrates the basic structure of a C++ program and how to output text to the console.

Sum: Shows how to perform arithmetic operations and calculate the sum of numbers.

## Downloading and installing of vs code and Mingw-


1] Click on the site https://code.visualstudio.com and then click on download for windows.

2] Now, your vs code will start downloading. Then click on the recent downloaded file in downloads tab.
 
3] Pop up window will appear, click on “I accept the agreement”. And click on next.
 
4] Now the setup installs vs code on your computer.
 
5] As now your vs code is installed, open it and install its other extensions like code runner and C/C++ in order to run the code. 
 
6] Now download MinGW which will compile your code. Site- MinGW - Minimalist GNU for Windows download | SourceForge.net

7.A pop up window will appear for the installation of MinGW. Click on install.
 
8] After this, various packages will appear. Tick all the required boxes you need for the c and c++ language.
 
9] Click on apply. Now MinGW is installed.
 
10] After this go to THIS PC click on ‘Advanced System Settings’. A pop-up window will appear, then go to ‘Environmental Variables’.
 
11] A pop-up window will appear. Click on new tab and add the link of the location of MingGW in THIS PC (in bin). And click on OK. Your Visual Studio Code is ready for use.

## Code - 
### 1. 
```
//Nikhil Raina 
//230701231093
//entc b1
//experiment 1
#include<iostream>
int main()
{
    std::cout<<"hello world";
    return 0;
}
```

### 2.
```
//Nikhil
//23070123093
//entc b1
//experiment 1B
#include <iostream>
using namespace std;
int main() 
{

    int a,b,product, sum,answer;
    float quotient;
    cout<<"Enter the value of a:\n";
    cin>>a;
    cout<<"Enter the value of b:\n";
    cin>>b;
    quotient=a/b;
    cout<<"The solution of a/b:"<<quotient<<"\n";
    product=a*b;
    cout<<"The solution of a*b:"<<product<<"\n";
    sum=a+b;
    cout<<"The solution of a+b:"<<sum<<"\n";
    answer=a-b;
    cout<<"The solution of a-b:"<<answer<<"\n";

    return 0;
}
```
### 3.
```
//Nikhil
//23070123093
//entc b1
//experiment 1B
#include<iostream>
using namespace std;
int main()
{
    string a;
    cout << "Enter your name ";
    getline(cin,a);
    cout<<"Hello  " <<a;
    return 0;
}
```
## Explanation - 
Hello World: The program includes the necessary header files and uses the standard output stream to print "Hello World" to the console.

Sum: These programs take input from the user, perform arithmetic calculations to find the sum of a number.

## Output -
1.![Screenshot 2024-08-12 140058](https://github.com/user-attachments/assets/1c94a3fd-78ee-4513-9424-db8f2d5fadef)

2.![Screenshot 2024-08-12 140157](https://github.com/user-attachments/assets/485df6bf-939b-406e-ac02-dbd788b6f63a)

3.![Screenshot 2024-08-12 140234](https://github.com/user-attachments/assets/70bf6937-2a4d-434a-a6be-a5f18f7a86b0)



## Conclusion -
These basic programs provide a solid foundation for understanding C++ syntax and basic operations by the setup of vs code and Mingw.

They illustrate how to use input/output streams, arithmetic operations, which are essential for complex programming tasks.
