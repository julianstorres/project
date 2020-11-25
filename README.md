# project
csc242 project
#include <iostream>
#include <string>
using std::cout;
using std::endl;
using std::cin;
double celcius( const int f)
{
	return ( 5.0 / 9.0 ) * (f - 32) ;
}
double fahrenheit( const int c)
{
	return ( 32 + ( c * 9.0 / 5.0) );
}
int main()
{
	int fahr = 102.0;
	int cel = 38.888;
	double ans_f = celcius(fahr);
	double ans_c = fahrenheit(cel);
	return 0;
	//I don't think I am doing this right
}
