# Quiz10.1



/*
 *  #WSQ14
 *  Created by George.16 on 4/23/15.
 *  Copyright (c) 2015 George.16. All rights reserved.
 *  Main: setprecision(num) << (numero o funcion) <<
 *  #TC1017
 *  Referencia: xxxxxxxxxxxxxxxxxxx
 *
 */

#include <iostream>

using namespace std;

int Suma(){
    int taco[12] = {0}, x, z, u = 0;
    
    cout << "Dame 10 numeros" << endl;
    
    for (int i = 1; i < 11; i++) {
        cout << "Numero"<< endl;
        cin >> x;
        taco[i] = x;
    }
    
    for(int i = 1; i < 11; i++){
        
        z = taco[i] % 3;
        
        if(z == 0){
            
            u = u + taco[i];
        }
        
    }
    
    return u;
}


int main(){
    int u;
    
    cout << "Suma de Vectores solo de los pares de 3 " << endl;
    
    u = Suma();
    
    cout << "resultado = "<< u << endl;
    
    return 0;
}
