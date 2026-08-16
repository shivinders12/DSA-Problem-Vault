# 2D Array - DS

* **Platform**: HackerRank
* **Difficulty**: Medium
* **Language**: C++11
* **Url**: https://www.hackerrank.com/challenges/2d-array/problem?isFullScreen=true

```cpp
#include <bits/stdc++.h>

using namespace std;

string ltrim(const string &);
string rtrim(const string &);
vector<string> split(const string &);

/*
 * Complete the 'hourglassSum' function below.
 *
 * The function is expected to return an INTEGER.
 * The function accepts 2D_INTEGER_ARRAY arr as parameter.
 */

int hourglassSum(vector<vector<int>> arr) {
    int maximum = INT_MIN;

    for (int i = 0; i < 4; i++) {
        for (int j = 0; j < 4; j++) {

            int sum = arr[i][j] 
                    + arr[i][j+1] 
                    + arr[i][j+2]
                    + arr[i+1][j+1]
                    + arr[i+2][j] 
                    + arr[i+2][j+1] 
                    + arr[i+2][j+2];

            maximum = max(maximum, sum);
```
