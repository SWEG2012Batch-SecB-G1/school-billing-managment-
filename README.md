# school-billing-managment-#include<iostream>
using namespace std;

struct student{
  char name[100];
  int roll_no;
  int grade;
  char section;
  int phone_no;
  };
  
  int size;
  
  int main() {
  	
  // accepts number of students and records inforamtion
  cout<<"Enter number of students:"<<endl;
  cin>>size;
  
     student s[size];
     for( int i=0; i<size; i++){
   
   	cout<<"Enter name of student "<<i+1<<": "<<endl;
   cin>>s[i].name;
    cout<<"Enter roll number: "<<endl;
   cin>>s[i].roll_no;
   cout<<"Enter grade: "<<endl;
   cin>>s[i].grade;
   cout<<"Enter section: "<<endl;
   cin>>s[i].section;
   cout<<"Enter phone no: "<<endl;
   cin>>s[i].phone_no;
  
	 }
// displays student record
	 
 cout<<"NAME\t      ROLL_NO\t    GRADE\t   SECTION\t   PHONE\t"<<endl;
    for( int i=0; i<size; i++){
	
	 cout<<s[0].name<<"       \t";
	 cout<<s[0].roll_no<<"    \t";
	 cout<<s[0].grade<<"                     \t";
	 cout<<s[0].section<<"             \t";
	 cout<<s[0].phone_no<<endl;
}
	 
  
  return 0;
  }
