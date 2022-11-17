TUGAS 7
--Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.
Stateless widget adalah widget yang tidak dapat berubah contohnya Icon, IconButton, dan text. Sedangkan stateful widget adalah widget yang sifatnya dinamis atau dapat berubah-ubah, contohnya mengubah nilai variable, warna, dll.

--Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya
Material App : sebagai root dari aplikasi
Scaffold : menyediakan struktur dasar dan styling dalam aplikasi
Column : Display children dalam format vertikal
Row : Display children dalam format horizontal
Text : Display string dalam satu baris
AppBar : display toolbar widgets, seperti title dan actions
Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.
berfungsi untuk memberitahu framework bahwa ada object yang berubah pada State, kemudian akan melakukan build ulang pada Widget tersebut. Variabel yang akan terdampak adalah variable yang diganti pada fungsi tersebut (tergantung fungsi tersebut ingin mengubah apa)

--Jelaskan perbedaan antara const dengan final.
final dapat digunakan untuk deklarasi variabel immutable yang nilainya sudah ataupun belum diketahui pada saat waktu kompilasi berjalan. Sedangkan Const dapat digunakan untuk deklarasi variabel immutable yang nilainya bersifat konstan dan harus sudah diketahui pada saat waktu kompilasi (Compile time) berjalan, artinya adalah nilai dari variabel tersebut harus sudah di berikan value secara langsung.

--Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.
Melakukan perintah flutter create counter_7

Mengimplementasikan widget - widget yang diperlukan pada program dan melakukan styling

Membuat fungsi untuk logika penambahan dan pengurangan angka.

--------------------------------------------------------------------------------------------------------------------
Tugas8

--Jelaskan perbedaan Navigator.push dan Navigator.pushReplacement.
Navigator.push = menambahkan atau push rute ke tumpukan rute/menimpa rute yang dikelola oleh Navigator 
Navigator.pushReplacement = menambahkan atau push rute ke tumpukan rute yang dikelola oleh Navigator dan membuang rute sebelumnya

--Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.
DropdownButton = membuat opsi memilih input
Spacer = membuat jarak antar widget
Container = menampung komponen
Form = menggabungkan input
TextFormField = memasukan input dari user
Card = membuat card untuk menampilkan input
TextStyle = membuat styling tulisan

--Sebutkan jenis-jenis event yang ada pada Flutter (contoh: onPressed).
OnPressed, OnChange, OnSaved, OnTap, ErrorEvent, dll

--Jelaskan bagaimana cara kerja Navigator dalam "mengganti" halaman dari aplikasi Flutter.
Mengimplementasi stack sehingga ketika push yang dimunculkan adalah yang urutan paling atas

--Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.
Menambahkan drawer yang berisi 3 navigasi pada hamburger di file data.dart, main.dart, form.dart
Membuat halaman form pada form.dart dengan membuat elemen input String untuk judul, int untuk nominal, dan dropdown untuk tipe budget dan button untuk menyimpan input
Membuat halaman data pada data.dar untuk menampilkan input yang telah diinput pada form.