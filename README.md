// suma de los 20 primeros numeros naturales
#include <iostream>
using namespace std;

int main ()
{
  int n = 1;
  int suma=0;

  while (n<21){
      suma=suma+n;
      n=n+1;
    
  }

    cout<<"La suma de los 20 primeros numeros naturales es "<<suma;
}
