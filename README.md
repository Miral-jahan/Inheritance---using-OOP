#include<<iostream.h>>
using namespace std;
class vehicle{
public:
string colour;
int year;
vehicle(string name,int year){
  this-> colour = name;
  this-> year = year;
  }
};
 class car: public vehicle {
public:
string brand;
car(string colour ,int year, string brand): vehicle(string colour,int year){
this-> brand = brand;
void get info(){
cout<<" colour: "<< colour<<endl;
cout<<" year: "<< year <<endl;
cout<<" brand: "<<brand <<endl;
}
int main(){
car c1( white,2025, BMW)
c1.get info();
return 0;
}


 
 




