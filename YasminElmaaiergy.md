<!---->
# My solution

```c++

#include <bits/stdc++.h>
#define nl "\n"
#define vt vector
#define ll long long
#define ld long double
using namespace std;
ll sum_all(ll num)
{
    return (num * (num + 1)) / 2; // ex: 1-->5
}
ll solve()
{
    ll n;
    cin >> n;
    return sum_all(n);
}
int main()
{
    cout << solve();
    return 0;
}
```
