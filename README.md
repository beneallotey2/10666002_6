# 10666002_6
Assignment 6 

# include <iostream>
using namespace std ;
int main ()
{
int a, b;
float arr[ 100];
cout << "Enter total number of elements (1 to 100): " ;
cin >> b;
cout << endl;
for ( a = 0 ; a < b; ++a)
{
cout << "Enter Number " << a + 1 << " : " ;
cin >> arr[a];
}
for (a = 1 ; a < b; ++a){
if (arr[ 0 ] < arr[a])
arr[ 0 ] = arr[a];
}
cout << "Largest element = " << arr[ 0 ];
return 0 ;
}
N
