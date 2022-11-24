# stack by STL
#include <iostream>
#include<stack>

using namespace std;

int main()
{
    stack<int> s;
    s.push(1);
    s.push(2);
    cout<<"element"<<s.top()<<endl;
    s.pop();
    cout<<"element"<<s.top()<<endl;

    return 0;
}
