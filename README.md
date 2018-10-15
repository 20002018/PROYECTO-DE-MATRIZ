# PROYECTO-DE-MATRIZ
MATRIZ
#include <iostream>
#include <iomanip>
#include <cmath>
#define a 500
#define a 500
using namespace std;
void Imprimirespacio(int e[a][a],int N);
int main() {
    int N;
    int e[a][a];
    cout<<"Ingrese numero de espacio:"<<" ";
    cin>>N;
    Imprimirespacio(e,N);
    return 0;

}

void Imprimirespacio(int e[a][a],int N) {
    for (int i = 0; i < N; i++) {
        for (int j = 0; j < N; j++) {
            if (N % 2 != 0) {

                cout << e[i][j] << " ";
            }
            else if (N++)
            {
               cout<<e[i][j]<<" ";
            }
        }
        cout << endl;
    }
}
