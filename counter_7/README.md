# Tugas 7 PBP - Elemen Dasar Flutter
# Trias Ahmad Fairuz - 2106633645
## Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.
State merupakan sebuah nilai yang terikat pada suatu widget yang dapat berubah-ubah. Sebuah widget dikatakan stateless jika bersifat statik dan tidak ada nilai yang akan berubah pada widget tersebut. Sebuah widget dikatakan statfeul jika bersifat dinamis, artinya state atau nilai yang terikat pada widget tersebut dapat berubah-ubah tergantung events tertentu yang didefinisikan pengembang. 

## Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.
- Scaffold -> Struktur layout sederhana dengan material design.
- Column -> Wadah widget secara vertikal
- Text -> Menampilkan teks 
- Visibility -> Menentukan kondisi visbilitas untuk suatu child 
- Container -> Sebagai wadah paling tinggi secara hirarki
- Row -> Wadah widget secara horizontal
- FloatingActionButton -> Button yang berada di bawah


## Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.
setState() berfungsi untuk memberi informasi kepada framework bahwa state dari suatu widget telah berubah. Ini khususnya diperlukan ketika ada perubahan pada interface yang ingin ditampilkan. Pada tugas ini, variabel yang terdampak dengan fungsi tersebut adlaah _counter yang memengaruhi teks ganjil atau genap.

## Jelaskan perbedaan antara const dengan final.
Const dan final sama-sama merupakan variabel immutable. Perbedaannya terdapat pada waktu nilai variabel tersebut diset. `final` di-set pada runtime, `const` di-set pada compile-time.

## Implementasi checklist
- Membuat aplikasi baru dengan command `flutter create counter_7`
- Membuat fungsi `_decrementCounter` untuk decrement counter
- Mengubah teks sesuai dengan nilai counter dengan menggunakan ternary operator. 
- Membuat widget Visibility dengan child FloatingActionButton untuk button decrement, dan assign fungsi _decrementCounter pada onPressed, serta menulis kondisi visible, yaitu ketika _counter>0
- Membuat widget FloatingActionButton untuk button increment dengan cara yang sama.
- add commit push