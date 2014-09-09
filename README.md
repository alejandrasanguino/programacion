programacion
============
// raises reales.h

#include "stdafx.h"
#include <iostream>
#include "conio.h"
#include "math.h"

using namespace std;

void main ()

{
float a, b, c, d, x, x1, x2, xr, xi;
	cout<<"ingrese a: ";
	cin>> a;
	cout<<"ingrese b: ";
	cin>> b;
	cout<<"ingrese c: ";
	cin>> c;
	d=b*b-4*a*c ;
	if (d>0)
	{
		x1=(-b+sqrt(d))/(2*a);
		x2=(-b-sqrt(d))/(2*a);
		cout<<"x1= " <<x1;
		cout<<"x2= "<<x2 ;
  }
  else 
  {if(d<0)
  {
		(xr=-b)/(2*a);
		x1*sqrt(-(b*b-4*a*c));
		cout<<"x1= "<<xr<<"+" <<x<<"i";
		cout<<"x2= " <<xr<<"-"<<xi<< "i";
}
  else 
  {x=-b/(2*a) ;
  cout<<"x= " <<x2;
}
}
  getch();
 }
