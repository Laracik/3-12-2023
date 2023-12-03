KODLAYICI:2
#include <iostream>
using namespace std;

void iki_ekle(int sayi, int ek_sayi) {
    for (int i = 0; i < ek_sayi; i++) {
        sayi += 2;
        cout << sayi << endl;
    }
}

int main() {
    iki_ekle(3, 5);
    return 0;
}
KODLAYICI3:
#include <iostream>
#include <string>
using namespace std;

void rozetToplamVeIsim(int rozetler[], int rozetSayisi, string ogrenciIsim) {
    int toplamRozet = 0;
    for (int i = 0; i < rozetSayisi; i++) {
        toplamRozet += rozetler[i];
    }
    cout << ogrenciIsim << " isimli ogrenci " << toplamRozet << " adet rozet kazanmistir." << endl;
}

int main() {
    int rozetler[] = {5, 3, 7, 2, 4}; // Örnek rozetler dizisi
    string ogrenciIsim = "Ahmet"; // Öğrenci ismi
    rozetToplamVeIsim(rozetler, 5, ogrenciIsim); // Fonksiyonu çağırma
    return 0;
}
