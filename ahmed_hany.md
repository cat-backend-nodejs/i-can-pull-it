#include <iostream>
using namespace std;
int main()
{
	long long n,answer=0;
	cin >> n;
	for (int i = n; i >0; i--)
	{
		answer += i;
	}
	cout << answer;
}
