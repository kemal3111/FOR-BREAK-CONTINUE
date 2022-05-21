# FOR-BREAK-CONTINUE
NAMA : MUHAMMAD KEMAL PASHA
NIM : 1217050098
KELAS : IF-B

1. FOR BREAK
#include <iostream>

using namespace std;

struct data_pelaku {
  int no;
  string nama;
  string umur;
  string kasus;
};

int main() {
  data_pelaku tersangka[] = {
    {
      1,
      "Kemal",
      "21",
      "Nyolong ayam"
    },
    {
      2,
      "Poco",
      "25",
      "Mukul ODGJ"
    },
    {
      3,
      "Ocop",
      "17",
      "Merampok bank keliling"
    },
    {
      4,
      "Pasha",
      "11",
      "Nyolong sendal pas jumatan"
    },
    {
      5,
      "Poly",
      "28",
      "Nyolong ikan di laut"
    },
    {
      6,
      "Pole",
      "28",
      "Nyolong emas di jawa"
    }
  };

  int notersangka = 6;

  

  for (int i = 0; i < 6; i++) {

    if (tersangka[i].no == notersangka) {
      cout << "berbuat ulah nih si " << tersangka[i].nama << " berumur " << tersangka[i].umur << " tahun ayo ditahan ! \n";

      break;
    }

    cout << "Pelaku bernama " << tersangka[i].nama << " berumur " << tersangka[i].umur << " tahun" << " tertangkap karena " << tersangka[i].kasus << "\n";
  }

}
                                                                                                                                                     
 2. FOR CONTINUE
#include <iostream>
using namespace std;

int main(){
    int x = 0;
    while (x < 50){
        if(x == 10){
              x++;
              continue;
        }
        cout << " " << x << ",";
        x++;
    }
    return 0;
}
