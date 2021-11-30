# grade-nilai-mahasiswa
#include <iostream>
using namespace std;

int main(){
	int nilai;
	cout<<"Masukan Nilai Mata Kuliah DDP Anda : "; cin>>nilai;
		
	if (nilai>=76)
	cout<<"Grade nilai : A"<<endl;

	else if (nilai>=71 && nilai<76)
	cout<<"Grade nilai : B+"<<endl;
	
	else if (nilai>=66 && nilai<71)
	cout<<"Grade nilai : B"<<endl;

	else if (nilai>=61 && nilai<66)
	cout<<"Grade nilai : C"<<endl;

	else if (nilai>=56 && nilai<61)
	cout<<"Grade nilai : D"<<endl;

	else if (nilai>=50 && nilai<56)
	cout<<"Grade nilai : E"<<endl;

	else if (nilai<50)
	cout<<"Grade nilai : F"<<endl;

	return 0;
}
