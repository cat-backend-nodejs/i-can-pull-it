#include <iostream>
using namespace std;

int main()
{

    int n;
    cout << "Enter a positive integer ";
    cin >> n;

   
    int result = n * (n + 1) / 2;
     cout << "Sum of positive integers up to " << n << ": " << result << endl;

    return 0;
}
