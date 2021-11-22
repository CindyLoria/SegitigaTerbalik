#include <iostream>
using namespace std;


int main(){
	string Nama;
	string Alamat;
	string Email;
	string NPM;
	
	//Input
	cout<<"Nama            = ";
	getline(cin,Nama);
	cout<<"Alamat Rumah    = ";
	getline(cin,Alamat);
	cout<<"Email           = ";
	getline(cin,Email);
	cout<<"NPM             = ";
	getline(cin,NPM);
	cin.ignore(1,'\n');
	
	//Output
	cout<<"Nama            = "<<Nama<<endl;
	cout<<"Alamat Rumah    = "<<Alamat<<endl;
	cout<<"Email           = "<<Email<<endl;
	cout<<"NPM             = "<<Nomor<<endl;
	
	return 0;
}
