# FLOYD-S-TRIANGLE.
How to make a programme on Floyd's triangle.
//FLOYD'S TRIANGLE
#include <iostream>
using namespace std;
int main()
{
  int i, j, k, v=1;
  cout<<"ENTER NUMBER OF ROWS OF FLOYD'S TRIANGLE:";
  cin>>k;
  for(i=1; i<=k; i++)
  {
  cout<<v<<" ";
  v++;
}
  cout<<endl;
}
return 0;
}
