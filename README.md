# 1.Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
Jawab :
Saya sudah mengikuti instruksi yang diberikan pada model dan telah menerapkannya. Pertama saya membuat folder html lalu membuat struktur htmlnya, kemudian saya membuat file cssnya dan membuat tampilan yang ditampilkan pada modul. Setelah membuat struktur html dan css, saya mulai mengubah dan menambahkan sesuatu dalam proyek yang saya kerjakan, seperti mengganti warna pada tampilan, mengganti dan menambahkan tulisan, dan merubah tata letak sebuah tulisan. Dibawah ini adalah hasil eksperimen saya
![Screenshot (43)](https://github.com/user-attachments/assets/e9d00fa2-2645-4b37-a474-83c929296c89)
![Screenshot (44)](https://github.com/user-attachments/assets/79a01843-e0d8-402f-b2b3-d882b491b345)

# 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan intro h1 {...}? berikan penjelasannya!
Jawab :
h1{ }  adalah selector elemen yang akan menerapkan gaya ke semua elemen h1 di halaman tersebut, tanpa memandang konteks atau lokasi elemen itu dalam HTML. Intro h1 adalah selector kombinasi yang lebih spesifik. Selector ini hanya akan menerapkan gaya pada elemen h1 yang berada di dalam elemen dengan id="intro". Jadi, hanya elemen h1 di dalam konteks elemen dengan ID intro yang akan mendapatkan gaya ini.
![Screenshot (37)](https://github.com/user-attachments/assets/d82655ff-11b7-455f-a261-07747a48bb76)
![Screenshot (38)](https://github.com/user-attachments/assets/b0230fc5-56c2-48e3-b25b-d5f69d8b1846)

# 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
Jawab :
Inline CSS ada prioritas tertinggi karena didefinisikan langsung pada elemen HTML, sementara internal css berada di tingkat yang lebih tinggi dari pada eksternal css karena berada dalam halaman yang sama. Dibawah ini adalah contohnya
![Screenshot (39)](https://github.com/user-attachments/assets/c1f61e61-edd2-44c4-bf22-c00e609eef09)
![Screenshot (40)](https://github.com/user-attachments/assets/825929e0-ef9e-4f28-8a02-050ac9310895)

# 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )
Jawab : 
Jika sebuah elemen HTML memiliki baik ID maupun class, maka CSS dengan selector ID memiliki prioritas lebih tinggi daripada selector class. Selector ID (#) memiliki prioritas lebih tinggi daripada selector class (.), karena ID dianggap unik dalam dokumen HTML. Jika sebuah elemen memiliki deklarasi CSS yang bertentangan dari class dan ID, maka gaya dari ID yang akan diambil.
![Screenshot (41)](https://github.com/user-attachments/assets/23589a57-c97b-4ee6-b3cb-7b0fda8255dd)
![Screenshot (42)](https://github.com/user-attachments/assets/5448170d-f56e-4091-90e8-a5df66ac9ea0)
