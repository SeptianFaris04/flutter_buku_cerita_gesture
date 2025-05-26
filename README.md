# flutter_buku_cerita_gesture

## Nama :

Muhammad Septian Farisasmita
4522210124

## Deskripsi Aplikasi

Petualangan Antariksa adalah aplikasi Flutter berbasis interaktif yang mengajak pengguna mengikuti cerita seorang astronot dalam misi membuka box misterius di luar angkasa. Pengguna dapat berinteraksi langsung dengan elemen-elemen di layar menggunakan gesture seperti drag, tap, double tap, dan long press untuk menyelesaikan misi.

## Screenshot Emulator :
![Page1](https://github.com/user-attachments/assets/baa21563-007c-42ce-a007-72e58a0ccd0e)
![Page2](https://github.com/user-attachments/assets/2f0c7e1c-7f43-4b52-b513-0e9b53165120)
![Page3](https://github.com/user-attachments/assets/567fab64-c06f-4913-85a1-1b29396c6050)
![Page4](https://github.com/user-attachments/assets/39cca9e0-08a3-4893-904b-b20e4cd985fc)

## Penjelasan Program :

- Title Page Menampilkan judul "Petualangan Antariksa" dan tombol untuk memulai petualangan. Ketika tombol diklik, halaman berpindah ke InteractiveScenePage.
- Interactive Scene Page Halaman inti interaktif tempat pengguna dapat:
  - Double Tap pada karakter astronot 👩‍🚀 untuk memunculkan dialog.
  - Long Press pada box 📦 untuk melihat petunjuk.
  - Drag kunci 🔑 ke arah box. Jika berhasil mengenai box, maka box akan terbuka 🔓 dan cerita berlanjut.
  - Geser (drag) latar belakang untuk menciptakan efek parallax sederhana dengan RawGestureDetector.
- End Page Setelah misi berhasil (box terbuka), pengguna diarahkan ke halaman akhir yang memberi ucapan selamat 🎉 dan tombol untuk mengulang petualangan.

## Cara Menjalankan Aplikasi :

flutter pub get flutter run
