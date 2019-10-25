# C-ideas
Ideas for c++ 
I have made this repository to learn more about GitHub as well as to leand c++
here i m giving u some code that might enhance ur ideas
#include <iostream.>
using namespace std;
#define max 10
int main()
{
	int number [max]={1,2,3,4,5,6,7,8,9,10};
	int index;
//	cout.set(ios::right);
	for(index=0;index<max;index++)
	{
		cout<<endl<<"the elements of array element are.."<<endl;
		cout.width(10);
		cout <<(index +1)<<"is";
		cout<<number[index];	
	}
		cout <<endl<<endl;
	return 0;
}
