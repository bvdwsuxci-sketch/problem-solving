#include <iostream>
#include <vector>
using namespace std;


int FindJudge(vector<vector<int>>& trust){
    int judge = trust[0][1];
    for (auto x : trust) {
        if (x[1] != judge) {
            return -1;
        }
    }
    return judge;


}


   



int main()
{
    
    vector<vector<int>> trust
    {
        {1,3},
        {2,3},
        {5,1}
    };
    int judge = FindJudge(trust);
    cout << judge;

}


