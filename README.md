#include <iostream>

using namespace std;

struct SinhVien { //Khai bao kieu du lieu
	string MaSinhVien;
	string HoTen;
	int Tuoi;
	float DiemTrungBinh;
};

int main(){
	//Khai bao bien
	SinhVien sv1;
	
	cout << "Nhap ma sinh vien: ";
	getline(cin, sv1.MaSinhVien);
	
	cout << "Nhap ho ten: ";
	getline(cin, sv1.HoTen);
	
	cout << "Nhap tuoi: ";
	cin >> sv1.Tuoi;
	
	cout << "Nhap diem trung binh: ";
	cin >> sv1.DiemTrungBinh;
	
	//Xuat thong tin
	cout << "***** Thong tin sinh vien *****" << endl;
	cout << "Ma sinh vien: " << sv1.MaSinhVien << endl;
	cout << "Ho Ten: " << sv1.HoTen << endl;
	cout << "Tuoi: " << sv1.Tuoi << endl;
	cout << "Diem trung binh: " << sv1.DiemTrungBinh << endl;
}
