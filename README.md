# praktikum07

Latihan 1 Membuat program Tukar nilai dari 2 buah variable
 
=>> Alur algoritma :

1. Mulai program
2. Void tukar (int &a, int &b)
3. masukkan nilai a
4. masukkan nilai b
5. int a,b:
	a=20;
	b=10;
6. cout << "Nilai a = " <<a<<endl;
7. cout << "Nilai b = " <<b<<endl;
8. cout << "Setelah ditukar<<endl;
9. tukar (a,b);
10. cout << "Nilai a = " <<a<<endl;
11. cout << "Nilai b = " <<b<<endl;
12. selesai

=>> Flowchart latihan 1 :

![flowchart1](https://user-images.githubusercontent.com/43899109/49293629-3f352080-f4e3-11e8-9437-01896d84fa14.jpg)


=>> Kode C++ program :

```

#include <iostream>

using namespace std;
void tukar(int &a, int &b){
    a=10;
    b=20;
}
int main()
{
    int a,b;
    a=20;
    b=10;
    cout << "Nilai a = " <<a<< endl;
    cout << "Nilai b = " <<b<< endl;
    cout << "SETELAH DITUKAR"<< endl;
    tukar(a,b);
    cout << "Nilai a = " <<a<< endl;
    cout << "Nilai b = " <<b<< endl;
    return 0;
}

```

=>> Hasil screenshoot latihan 1 :


![sslatihan1](https://user-images.githubusercontent.com/43899109/49293632-3fcdb700-f4e3-11e8-80bd-65c63f6cdfb9.jpg)


=>> Flowchart latihan 2 :

=>> Kode C++ program :


#include <iostream>

```

using namespace std;
int kali (int m, int n)
{
    int i,hasil=0;
    for(i=1;i<=n;i++)
        hasil+=m;
    if (n<0)
        {
        return(-hasil);
        }
    else
        {
        return(hasil);
        }
}
int main()
{
    int a,b;
    cout<<"Masukan Bilangan :";
    cin>> a;
    cout<<"Masukan Bilangan :";
    cin>> b;
    cout << "\n\nHasil dari " << a <<" X "<< b <<" = "<<kali(a,b);
    return 0;
}

```

![flowchart2](https://user-images.githubusercontent.com/43899109/49293631-3fcdb700-f4e3-11e8-8653-c7db13b8a5ca.jpg)


=>> Hasil screenshoot latihan 2 :

![sslatihan2](https://user-images.githubusercontent.com/43899109/49293633-3fcdb700-f4e3-11e8-8f0d-257ce43989fe.jpg)
