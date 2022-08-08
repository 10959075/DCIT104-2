# DCIT104-2
Fundamentals of Programming 

#include <iostream>
using namespace std;

int main() {

    bool isPrimeNumber = true 
    int i; 
    int num;
    int reach = 100;
    int sum = 0; 
    for(int i = 2; i < 100; i++)
    {
        if(num % i == 0)
        {
            if(isPrimeNumber)
            {
                sum = sum + i;
            }
        }
        }
    }
    cout << sum << endl;
    return 0;
}
