## Instalasi

1.  Dengan File APK <br>
    dapat diinstal dengan mendownload file apk yang tertera pada folder file_apk, <br>
    kemudian menginstalnya pada android anda <br>
2.  Dengan React Native <br>
    • Instal terlebih dahulu node.js versi 12 atau lebih (Jika sudah memiliki, skip bagian ini) <br>
    • Download semua file pada folder project <br>
    • Gunakan terminal lalu lakukan perintah berikut <br>
    -> cd ReactNative <br>
    -> npm start <br>

Setelah terpasang beberapa aplikasi yang dibutuhkan, kemudian buka vscode lalu dapat menggunakan perintah:
- jika belum install npm, masukkan perintah "npm install" 
- npm run android

## Pembuatan Aplikasi

1. Langkah awal kita pecah halaman kedalam 3 file yaitu App.js, Home.js dan hasilPencarian.js <br>
   App.js => secara garis besar akan berisikan navigator untuk berpindah antara halaman home.js dan hasilPencarian.js <br>
   Home.js => secara garis besar akan berisikan halaman home yang berisikan 3 text input dan 1 button <br>
   hasilPencarian.js => secara garis besar akan berisikan halaman yang menampilkan data sesuai dengan inputan yang diberikan <br>

2. Lakukan pembuatan navigator pada app.js dalam hal ini akan digunakan stackNavigator <br>

3. Bentuk halaman home sesuai keriterian tugas <br>
   kemudian tambahkan props untuk dapat membaca dan mengirim inputan pada text input <br>

4. Bentuk halaman hasilPencarian sesuai dengan keriterian tugas <br>
   Pastikan props yang dikirim dapat diterima halaman ini <br>
   Lakukan pengecekan menggunakan if, data yang sesuai dengan inputan, lalu tampilkan data tersebut <br>

<b>Penjelasan Aplikasi:</b>

Aplikasi ini dapat melakukan pencarian jadwal keberangkataan pesawat

<b>Screenshot Aplikasi:</b>

Default:

![](ScreenshotApp/daftar.png) <br>

Flight Available:

![](ScreenshotApp/home.png) <br>

Not Flight Available:

![](ScreenshotApp/hasil.png) <br>

## Sumber

1. https://reactnative.dev/
2. https://reactnavigation.org/
3. https://fontawesome.com/v5/docs/web/use-with/react-native
4. PPT Perkuliahan Pemrograman Aplikasi Mobile 2022
