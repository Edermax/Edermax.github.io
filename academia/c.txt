#include <iostream>

using namespace std;

int main()
{
    float valor, juros, total;
    cout<<"valor" <<endl;
    cin>>valor;
    cout<<"juros" <<endl;
    cin>>juros;
    total = valor + (valor + juros); 
    cout<<"total: "<< total <<endl;
    return 0;
}