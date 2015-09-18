# -WSQs07-TC1017

#include  <iostream>

using namespace std;

int main()
{
	
	int n1, n2, suma=0, contador;

	cout << "Dame el primer numero" << endl;
	
	cin >> n1;

	cout << "Dame el segundo numero" << endl;
	
	cin >> n2;

	contador = n1;

	do
	
	{
	
		suma = suma + contador;
	
		contador = contador +1;
	
	} while (contador <= n2);

	cout<< "La suma del rango entre los numeros"<< n1 <<" y "<< n2 <<" es "<< suma << endl;
	
	return 0;

}
