#include <iostream>
using namespace std;
int main()
{
*int i, y, b, d, f;
	cout << "4 basamakli bir sayi giriniz\n";
	cin >> i;
	if (i > 9999) {
		cout << "lütfen 4 basamaklı sayı giriniz\n";
	}
	else {
		f = i / 1000;
		i = i - (f * 1000);
		y = i / 100;
		i = i - (y * 100);
		b = i / 10;
		i = i - (b * 10);
		d = i;
		cout << "binler basamagi = " << f << "\n";
		cout << "yuzler basamagi = " << y << "\n";
		cout << "onlar basamagi = " << b << "\n";
		cout << "birler basamagi = " << d << "\n";
	}
return 0;
}
