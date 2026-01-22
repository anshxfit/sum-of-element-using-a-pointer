# c++ sum of elements using a pointer
# include<iostream.h>
#include<conio.h>
void main()
{
clrscr();
int arr[5]={10,20,30,40,50};
int*ptr;
int sum=0,i;
ptr=arr;
for(i=0,i<5;i++){
sum=sum+*(ptr+i);
}
cout<<"sum of array elements="<<sum;
getch();
}
