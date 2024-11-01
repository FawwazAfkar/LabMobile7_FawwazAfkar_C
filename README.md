# Langkah untuk Proses Login di Ionic

### 1. **Membuat Form Login**

   - Di komponen login (misalnya `login.page.ts`), buat form dengan `FormBuilder` dari Angular untuk mengambil data `email` dan `password` pengguna
   - Pada `login.page.html`, tambahkan elemen form untuk `email` dan `password` dengan `ion-input`

### 2. **Membuat AuthService untuk Menangani Login**

   - Buat sebuah service bernama `AuthService` menggunakan Angular CLI
   - Dalam `auth.service.ts`, tambahkan fungsi `login` yang menggunakan `HttpClient` untuk mengirim data login ke API

### 3. **Memanggil AuthService dari Login Page**

   - Di `login.page.ts`, panggil `AuthService` dan kirim data form jika `loginForm` valid

### 4. **Membuat Auth Guard untuk Rute Terproteksi**

   - Buat guard bernama `AuthGuard` untuk memastikan pengguna hanya bisa mengakses halaman tertentu jika sudah login

### 5. **Membuat Fungsi Logout**

   - Tambahkan tombol logout di `home.page.html`, dan buat fungsi `logout`

## Tampilan

## Screenshot
![login](src/assets/img/loginpage.png)
![home](src/assets/img/homepage.png)

### Video Demo
![demo](src/assets/videos/2024-11-01%2015-41-04.mkv)











