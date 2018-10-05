#include <iostream>
using namespace std;

int main()
{ int opcion {};
    
    cout << "1. Dollares a Lempiras\n2.Libras Esterlinas a Dollares.\n3. Euros a Dollares.\n Elija una opcion: ";
    cin >> opcion;

switch (opcion) {
    
    case 1:{
   const double lempiras_a_dollares {23.66}; 
    double dollares_a_cambiar;
    
     cout << "Ingrese cantidad de dollares con 2 decimales: ";
    cin >> dollares_a_cambiar;
    
    cout << "Su cambio de Dollares a Lempiras es de: " << dollares_a_cambiar*lempiras_a_dollares << endl; 
    break;}
    
   case 2:{
   const double libras_a_dollares {1.30}; 
    double libras_a_cambiar;
     cout << "Ingrese cantidad de Libras Esterlinas con 2 decimales: ";

    cin >> libras_a_cambiar;
    
    cout << "Su cambio de Libras a Dollares es de: " << libras_a_cambiar*libras_a_dollares<< endl; 
   break;}
    case 3:{
    
   const double euros_a_dolar {1.15}; 
    double euros_a_cambiar;
     cout << "Ingrese cantidad de Euros con 2 decimales: ";

    cin >> euros_a_cambiar;
    
    cout << "Su cambio de Euros a Dollares es de: " << euros_a_cambiar*euros_a_dolar<< endl;
    break;}
    
    default: 
            cout <<"Please choose an option :)!";

}

cout << endl;
}
