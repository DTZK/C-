# C- (file name)
#C++ programming (this is a comment)
#include <iostream>

using namespace std;

int main()
{
   cout << "Hi, I am magikra" << endl; 
   
   return 0;
}

hellomake: C-.c
        gcc -o hellomake C-.c -I.
   
