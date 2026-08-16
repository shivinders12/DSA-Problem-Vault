# Arrays - DS

* **Platform**: HackerRank
* **Difficulty**: Medium
* **Language**: C++11
* **Url**: https://www.hackerrank.com/challenges/arrays-ds/problem?isFullScreen=true

```cpp
#include <bits/stdc++.h>

using namespace std;

string ltrim(const string &);
string rtrim(const string &);
vector<string> split(const string &);

/*
 * Complete the 'reverseArray' function below.
 *
 * The function is expected to return an INTEGER_ARRAY.
 * The function accepts INTEGER_ARRAY a as parameter.
 */
vector<int> reverseArray(vector<int> a) {
    reverse(a.begin(), a.end());
    return a ;
}

int main()
{
    ofstream fout(getenv("OUTPUT_PATH"));

    string arr_count_temp;
    getline(cin, arr_count_temp);

    int arr_count = stoi(ltrim(rtrim(arr_count_temp)));

    string arr_temp_temp;
    getline(cin, arr_temp_temp);
```
