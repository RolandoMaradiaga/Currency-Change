# Currency-Change
Beginners Currency Money App
// C++ Code


#include <iostream>
#include <stdio.h>

using namespace std;

double lempiras_a_dollares {23.66};
double dollares_a_cambiar;

int main()
{
    cout << "Ingrese cantidad de dollares con 2 decimales: ";
    
    cin >> dollares_a_cambiar;
    
    cout << "La cantidad total de lempiras es de: "<< dollares_a_cambiar* lempiras_a_dollares << "\n";
    
    
}
