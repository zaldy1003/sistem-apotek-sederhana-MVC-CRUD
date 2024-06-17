## PRA TUBES CALON ASISTEN (CA) 2024 ICLABS FIKOM UMI (WEB)

## SISTEM APOTEK SEDERHANA MVC & CRUD :smiling_imp:
> [!NOTE]
> MUHAMMAD AFRIZALDI ATTALAH - 13020220057


> [!IMPORTANT]
> Key information users need to know to achieve their goal.

## THE PATH
...
> PREPARE
>> Install Discord
>> Add Plugin PlantUML
>> Semantic Commit
> DESIGN
>> UML
>> ERD
>> UI/UX
> IMPLEMENT
>> Konsep MVC
> SERVER
>> Konfigurasi 
>> DNS

> [!WARNING]
> Using PHP NATIVE
> Learn more JavaScript (Option)
> Learn more Ajax (Option)


> [!CAUTION]
> PHP VERSION LASTES

[NOTE]
>Mekanisme Penambahan Berbagai Obat dalam Satu Pesanan
>>1. Keranjang Belanja:
Saat pengguna memilih obat dan menambahkannya ke keranjang belanja, sistem akan menyimpan informasi obat dan jumlahnya di keranjang belanja.
Keranjang belanja dapat diimplementasikan dengan berbagai cara, seperti:
-Session: Data keranjang belanja disimpan di server dalam variabel session yang terkait dengan ID pengguna.

-Database: Data keranjang belanja disimpan di tabel terpisah di database.

-Cookie: Data keranjang belanja disimpan di browser pengguna dalam cookie.
>>3. Formulir Pesanan:
Ketika pengguna ingin melakukan pemesanan, sistem akan menampilkan formulir pemesanan yang berisi informasi berikut:
-Rincian obat yang ada di keranjang belanja, termasuk nama obat, harga, dan jumlah.

-Informasi pengguna, seperti nama, alamat, dan email.
>>4. Menyimpan Pesanan:
Ketika pengguna mengirimkan formulir pemesanan, sistem akan melakukan validasi data.
Jika data valid, sistem akan:
-Menyimpan informasi pesanan di tabel Pesanan, termasuk informasi pengguna, alamat, metode pembayaran, dan tanggal pemesanan.
Untuk setiap obat yang dipesan, sistem akan membuat entri baru di tabel Detail_Pesanan, termasuk ID pesanan, ID obat, dan jumlah obat yang dipesan.
Mengirimkan email konfirmasi kepada pengguna dengan detail pesanan.
