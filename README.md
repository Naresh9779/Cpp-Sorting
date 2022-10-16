# C-Sorting
#include<iostream>
using namespace std;
int main ()
{
    int a[20];
int i,j,k,n;

cout<<"Enter THe NUmber Of ELement : ";
cin>>n;
cout<<"Enter the Element in Ascending order : ";
for(i=0;i<n;i++)
{

cin>>a[i];

}

cout<<"Enter The Element Which You Want To Add : ";
cin>>j;
char c='y';
while(c=='y')
{
if (n>=20)
{

    cout <<"Over Flow";
    exit(1);
}
int t=n-1;
int l=0;
while(n>t)
if(a[l]<j)
{
    l++;
}
else
{
    a[l]==j;

t=n+2;
n++;




for(i=0;i<n;i++)
{

cout<<a[i]<<"\t";

}

cout<<" \n PRess Y TO Continue OR N TO Exit ";
cin>>c;

}






}



}
