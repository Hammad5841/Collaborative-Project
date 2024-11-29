	#include<iostream>
using namespace std;
int main()
{
string gender,marital_status;
int age;
cout<<"Enter your gender :";
cin>>gender;
cout<<"Enter your age :";
cin>>age;
cout<<"Enter the marital_status :";
cin>>marital_status;
if(marital_status=="married")
{
if(marital_status=="married")
{
cout<<"the driver is insured";
}
else
{
cout<<"driver is not insured";
}
}
else if(gender=="male")
{
if(age>30)
{
cout<<"the driver is insured";
}
else
{
cout<<"driver is not insured";
}
}
else if(gender=="female")
{
if(age>25)
{
cout<<"the driver is insured";
}
else
{
cout<<"driver is not insured";
}
}
return 0;
}
