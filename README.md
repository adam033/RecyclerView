# RecyclerView
## Pengumpulan Modul RecyclerView Grid And List
#### Teori <br>
Pada materi sebelumnya kita telah belajar bagaimana menampilkan kumpulan data dalam bentuk sebuah list. Kita menggunakan obyek listview untuk menampilkan data-data yang berasal dari kontak di peranti pengguna ke layar. Sangat sederhana tapi sangat berarti. Mengapa? Pada dasarnya interaksi umum antara pengguna dengan aplikasi dalam menampilkan data dengan jumlah yang banyak adalah dengan menggunakan list yang bisa di-scroll ke atas dan ke bawah.
Listview menjadi komponen pertama yang mengakomodasi hal tersebut. Namun semenjak Google meluncurkan pendekatan material design, recyclerview menjadi pilihan pertama yang harus digunakan. Anda masih bisa menggunakan kedua komponen tersebut secara berdampingan dalam satu aplikasi.
RecyclerView adalah sebuah komponen tampilan (**widget**) yang lebih canggih ketimbang pendahulunya listview. Ia bersifat lebih fleksibel. RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar. Terlebih jika Anda memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime). <br>

1.	**RecyclerView** dan LayoutManager : Komponen antarmuka yang bertugas untuk menampilkan data set yang dimiliki di dalamnya. Layoutmanager akan mengatur posisi tampilan data baik itu secara list (vertikal), grid (baris dan kolom) atau staggered grid (grid yang memiliki susunan tak seragam / tak beraturan).
2.	**Adapter** : Komponen yang akan mengatur bagaimana menampilkan data set ke dalam RecyclerView. Di sinilah terjadi proses pengisian tampilan (ViewInflate) dari file layout xml untuk tiap elemen dari data yang sebelumnya terpasang (bind) ke dalam RecyclerView.
3.	**Dataset** : Kumpulan data yang dimiliki dan ingin ditampilkan. Bisa berupa array, list maupun obyek map.
4.	**Item Animator** : Ini yang spesial. Kita bisa pasang animasi untuk tiap item di dalamnya. Contoh animasi yang umum seperti penambahan (add) dan penghapusan (removal) item. Kita akan mempelajari hal ini pada materi terpisah.

![Alt Text](https://github.com/adam033/RecyclerView/blob/master/Screenshot%20(436).png)
![Alt Text](https://github.com/adam033/RecyclerView/blob/master/Screenshot%20(437).png)
![Alt Text](https://github.com/adam033/RecyclerView/blob/master/Screenshot%20(438).png)
