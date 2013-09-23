--------
========
#include<iostream>
using namespace std;
int tem(int x){
        int f,c;
		f=x;
		c=5/9*(f-32);
		return c;
               }
int main()
{cout<<"输入华氏温度"<<endl;
 int y;
 cin>>y;
 cout<<"摄氏温度为"<<tem(y)<<endl;
}
