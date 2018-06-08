#include <iostream>

using namespace std;

//Global Variables
char name[30];
int year;

//Main Function
int main()
{
    cout<<"Enter your full name: ";
    cin>>name;
    cout<<name[0];
    cout<<"Enter your birth year: ";
    cin>>year;
    cout<<endl<<endl;
    return 0;
}
