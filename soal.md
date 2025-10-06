# 🧭 PRE TEST WEB DEVELOPER


## 1. Apa fungsi utama dari framework Laravel?
- [ ] a. Membuat aplikasi desktop  
- [ ] b. Membuat situs web statis  
- [x] c. Membuat aplikasi web dinamis dengan struktur MVC  
- [ ] d. Membuat game online  

---

## 2. Dalam Laravel, file konfigurasi database terletak di folder:
- [ ] a. /routes  
- [ ] b. /database  
- [x] c. /config  
- [ ] d. /resources  

---

## 3. Command artisan yang digunakan untuk membuat model baru adalah:
- [ ] a. php artisan make:controller  
- [x] b. php artisan make:model  
- [ ] c. php artisan make:migration  
- [ ] d. php artisan make:seeder  

---

## 4. Fungsi `Route::get()` dalam Laravel digunakan untuk:
- [ ] a. Menghapus data dari database  
- [x] b. Menangani permintaan GET ke URL tertentu  
- [ ] c. Menyimpan data baru ke database  
- [ ] d. Mengedit data melalui API  

---

## 5. Apa kegunaan file `.env` pada proyek Laravel?
- [ ] a. Menyimpan library eksternal  
- [x] b. Menyimpan konfigurasi sensitif seperti database dan mail  
- [ ] c. Menyimpan file log aplikasi  
- [ ] d. Menyimpan data user  

---

## 6. Dalam Laravel, Blade template digunakan untuk:
- [ ] a. Mengelola database  
- [ ] b. Menulis perintah artisan  
- [x] c. Membuat tampilan dengan sintaks templating  
- [ ] d. Mengatur routing  

---

## 7. Sintaks Blade untuk mencetak data variabel adalah:
- [x] a. {{ $data }}  
- [ ] b. <?php echo $data ?>  
- [ ] c. print($data)  
- [ ] d. @echo($data)  

---

## 8. Cara mendefinisikan route dengan parameter di Laravel adalah:
- [ ] a. Route::get('/user', UserController::class);  
- [x] b. Route::get('/user/{id}', [UserController::class, 'show']);  
- [ ] c. Route::post('/user/{id}', [UserController::class, 'store']);  
- [ ] d. Route::group('/user', [UserController::class, 'show']);  

---

## 9. Dalam Eloquent, method untuk mengambil semua data dari model User adalah:
- [ ] a. User::find();  
- [ ] b. User::get();  
- [x] c. User::all();  
- [ ] d. User::first();  

---

## 10. Untuk memperbarui data dalam tabel menggunakan Eloquent, digunakan perintah:
- [ ] a. User::create([...]);  
- [x] b. User::find($id)->update([...]);  
- [ ] c. User::destroy($id);  
- [ ] d. User::save([...]);  

---

## 11. Fungsi `php artisan migrate` digunakan untuk:
- [x] a. Menjalankan migration dan membuat tabel di database  
- [ ] b. Menghapus tabel database  
- [ ] c. Membuat model baru  
- [ ] d. Menjalankan seeder data  

---

## 12. File migration digunakan untuk:
- [ ] a. Menulis log aktivitas user  
- [x] b. Mengatur struktur database (tabel dan kolom)  
- [ ] c. Mengatur tampilan frontend  
- [ ] d. Mengatur konfigurasi .env  

---

## 13. Di Laravel, method `with()` digunakan untuk:
- [ ] a. Menjalankan query SQL mentah  
- [x] b. Melakukan eager loading relasi antar model  
- [ ] c. Menghapus data di database  
- [ ] d. Mengembalikan response JSON  

---

## 14. Apa fungsi dari `tinker` di Laravel?
- [ ] a. Mengelola routing  
- [x] b. Menjalankan perintah database interaktif  
- [ ] c. Mengatur file konfigurasi  
- [ ] d. Membuat controller baru  

---

## 15. Pada Laravel, method `store()` biasanya terdapat di dalam:
- [ ] a. Model  
- [ ] b. Middleware  
- [x] c. Controller  
- [ ] d. View  

---

## 16. Perintah untuk membuat controller baru di Laravel adalah:
- [ ] a. php artisan make:view  
- [x] b. php artisan make:controller  
- [ ] c. php artisan controller:create  
- [ ] d. php artisan controller:generate  

---

## 17. Dalam Eloquent, relasi One To Many didefinisikan dengan:
- [ ] a. hasOne()  
- [ ] b. belongsTo()  
- [x] c. hasMany()  
- [ ] d. belongsToMany()  

---

## 18. Fungsi `request()->input('name')` digunakan untuk:
- [ ] a. Mengambil data dari variabel session  
- [x] b. Mengambil input dari form  
- [ ] c. Menghapus file upload  
- [ ] d. Menampilkan route aktif  

---

## 19. Untuk menampilkan semua data user dalam view, sintaks Blade yang benar adalah:
- [x] a. @foreach ($users as $user) {{ $user->name }} @endforeach  
- [ ] b. foreach ($users as $user) echo $user->name;  
- [ ] c. @loop ($users as $user) {{ $user->name }}  
- [ ] d. @for ($users as $user) {{ $user->name }}  

---

## 20. Middleware di Laravel berfungsi untuk:
- [ ] a. Mengatur desain tampilan web  
- [x] b. Menyaring atau memeriksa request sebelum masuk ke controller  
- [ ] c. Menjalankan migration database  
- [ ] d. Mengatur routing antar halaman  
