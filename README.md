# richal_test
richal_test


- pertama instal requirements yang telah di siapkan
- buat struktur db yang telah di siapkan , db yang digunakan postgresql
- aplikasi terdapat 2 role yaitu sys dan cus , sys sebagai admin dan cus sebagai customer
- pertama silahkan buat user dgn role sys , dengan ID "USER00001" , dan pin berupa angka
- lalu silahkan login ke aplikasi 
- sys admin mendapatkan akses 5 menu (home, upload koleksi dvd, report, persetujuan sewa, logout)
- pertama menu home berisi list dvd yang dapat di sewakan ke customer, dengan ordering by tanggal buat
- kedua menu upload koleksi dvd, admin dapat upload koleksi dvd dengan file csv yang formatnya sudah disediakan
- ketiga menu report, menu report berisi list daftar dvd yang dapat di update dari judul, stock, rating, deskirpsi
- keempat menu persetujuan, menu yang dapat diakses admin guna persetujuan sewa dvd dari customer, terdapat 2 persetujuan yaitu tolak dan setuju
- logout , menu untuk menghapus session admin
- role user customer, menu signup, mendapatkan akses menu home , history sewa, logout
- menu signup digunakan untuk mendaftar user baru
- menu home berisi list dvd yang dapat di sewakan ke customer, dengan ordering by tanggal buat, terdapat button sewa di setiap list data, jika di klik maka masuk pada menu detail sewa
- menu detail terdapat detail film dan customer diwajibkan menupload bukti pembayaran sewa dvd
- menu history sewa, list history sewa dvd yang telah diajukan customer 
- menu logout menu untuk menghapus session 
