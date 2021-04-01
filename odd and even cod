#include<iostream> 
using namespace std; 
class number{ 
 int x; 
 static int count; 
public: 
    void read(){ 
     cout<<"Please enter the number:"; 
     cin>>x; 
 } 
 void show() 
 { 
  cout<<x<<" "; 
  } 
 static void print_count(){ 
 cout<<"The count is:"<<count<<endl; 
 } 
 void even(number); 
}; 
void number::even(number c){ 
 x=c.x; 
  
 ~5 ~ 
 
if(c.x%2==0) 
 { 
  cout<<"The number is even:"; 
  cout<<c.x<<endl; 
  count++; 
 } 
 else{ 
  cout<<"The number is odd:"; 
  cout<<x<<endl; 
  count--; 
 } 
}  
int number::count=1; 
int main() 
{ 
    number y[4]; 
 for(int i=0;i<4;i++) 
 y[i].read(); 
 cout<<"Show the number:"; 
 for(int i=0;i<4;i++) 
 y[i].show(); 
 cout<<"\n"; 
 for(int i=0;i<4;i++) 
 y[i].even(y[i]); 
 ~6 ~ 
 
 number::print_count(); 
    return 0; 
} 
