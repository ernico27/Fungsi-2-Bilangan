# Fungsi-2-Bilangan

    #include<iostream>
    using namespace std;
    int main()
    {
    char pilihan;
    cout << "\t\t ========================== \n";
    cout << "\t\t Program fungsi 2 bilangan \n";
    cout << "\t\t ========================== \n";
    cout << "\t\t 1. pertambahan \n";
    cout << "\t\t 2. pengurangan \n";
    cout << "\t\t 3. perkalian \n";
    cout << "\t\t 4. pembagian \n";
    cin >> pilihan;
    switch (pilihan)
    {
    case '1':
        float satu,dua,pertambahan;
        cout << "\t\t Pertambahan \n";
        cout << "\t\t ------------ \n";
        cout << "\t\t Masukkan bilangan 1 = ";
        cin >> satu;
        cout << "\t\t Masukkan bilangan 2 = ";
        cin >> dua;
        pertambahan=satu+dua;
        cout << "\t\t Hasil pertambahan ke-2 bilangan adalah = " << pertambahan;
        break;
    case '2':
        float tiga,empat,pengurangan;
        cout << "\t\t Pengurangan \n";
        cout << "\t\t ------------ \n";
        cout << "\t\t Masukkan bilangan 1 = ";
        cin >> tiga;
        cout << "\t\t Masukkan bilangan 2 = ";
        cin >> empat;
        pengurangan=tiga-empat;
        cout << "\t\t Hasil pengurangan ke-2 bilangan adalah = " << pengurangan;
        break;
    case '3':
        float lima,enam,perkalian;
        cout << "\t\t Perkalian \n";
        cout << "\t\t ------------ \n";
        cout << "\t\t Masukkan bilangan 1 = ";
        cin >> lima;
        cout << "\t\t Masukkan bilangan 2 = ";
        cin >> enam;
        perkalian=lima*enam;
        cout << "\t\t Hasil perkalian ke-2 bilangan adalah = " << perkalian;
        break;
    case '4':
        float tujuh,delapan,pembagian;
        cout << "\t\t Pembagian \n";
        cout << "\t\t ------------ \n";
        cout << "\t\t Masukkan bilangan 1 = ";
        cin >> tujuh;
        cout << "\t\t Masukkan bilangan 2 = ";
        cin >> delapan;
        pembagian=tujuh/delapan;
        cout << "\t\t Hasil pembagian ke-2 bilangan adalah = " << pembagian;
        break;
    default:
        cout << "Anda salah pilihan !";
    }
    return 0;
    }
    
## Hasilnya

![img](https://github.com/ernico27/Fungsi-2-Bilangan/blob/master/fungsi%202%20bilangan.png?raw=true)
