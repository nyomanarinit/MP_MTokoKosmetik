# MINI PROJECT
NAMA: NYOMAN ARINI TRIRAHAYU

NIM: 2309116002

KELAS: SISTEM INFORMASI A

MATA KULIAH: PTRAKTIKUM ALGORITMA DAN STRUKTUR DATA

## MP1_MTokoKosmetik
~Penejlasan Program

Program ini merupakan aplikasi manajemen produk kosmetik sederhana dengan menggunakan terminal sebagai antarmuka pengguna. 

1.  program akan membersihkan terminal dan mengimport modul yang dibutuhkan, yaitu `os` untuk membersihkan terminal dan `PrettyTable` untuk menampilkan data dalam bentuk tabel.

2. terdapat definisi kelas `Produk` yang digunakan untuk merepresentasikan produk kosmetik. Kelas ini memiliki atribut seperti kode, nama, harga, stok, dan kategori.

3. ada definisi kelas `TokoKosmetik` yang digunakan untuk manajemen produk. Kelas ini memiliki fungsi-fungsi seperti `tambah_produk`, `lihat_produk`, `update_produk`, dan `hapus_produk`.

4. Di dalam fungsi utama (`main()`):
   - Program membuat objek dari kelas `TokoKosmetik` sebagai toko kosmetik default.
   - Program akan memasuki loop utama yang menampilkan menu utama kepada pengguna.
   - Pengguna diminta untuk memilih opsi (angka) sesuai dengan menu yang ditampilkan.
   - Setiap pilihan akan memicu fungsi-fungsi yang sesuai pada objek `TokoKosmetik` atau memberikan pesan kesalahan jika input tidak valid.
   - Pilihan 1 berfungsi untuk menambahkan produk
   - Pilihan 2 berfungsi untuk lihat produk
   -  Pilihan 3 berfungsi untuk update produk
   -  Pilihan 4 berfungsi untuk hapus produk
   -  Pilihan 0 berfungsi untuk menghentikan program
   - Loop akan terus berjalan sampai pengguna memilih untuk keluar (pilihan 0).

5. Output yang mungkin dihasilkan:
   - Pesan kesalahan jika data produk tidak lengkap atau ada duplikat kode produk saat menambahkan produk baru.
   - Daftar produk dalam bentuk tabel jika pengguna memilih untuk melihat daftar produk.
   - Pesan sukses atau pesan bahwa produk tidak ditemukan saat mengupdate atau menghapus produk.
   - Pesan terima kasih saat pengguna memilih untuk keluar.

## MP2_MTokoKosmetik

### Penjelasan dan Output Program.


1. Tampilan Awal Program
   Pada tampilan awal program user di berikan 5 pilihan yaitu 1.Tambah Produk, 2.Lihat Daftar Produk, 3.Update Produk, 4.Hapus Produk, dan 0.Keluar.

   
![Cuplikan layar 2024-03-02 084512](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/9f0e108f-0843-4a3c-a6fa-d754153e7db7)



2. Tampilan Program
   
   -1.Tambah Barang
   Jika User memilih 1.Tambah Barang maka akan diberikan menu lagi dengan 4 pilihan menu tambah barang yaitu 1.Tambah Barang di Awal, 2.Tambah Barang di Akhir, 3.Tambh Barangf di antara Node, dan 0.Kembali.

   
   ![Cuplikan layar 2024-03-02 084533](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/bc5e9916-9a0f-4b13-a857-5a108d6df60a)
   ![Cuplikan layar 2024-03-02 084548](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/1d439f35-5760-484e-b0b9-8c5bad777f44)

   

      *1.Tambah Barang di Awal
         Tambah barang di awal artinya barang yang akan user tambahkan akan otomatis berada di awal atau di paling atas pada list barang. Jika user memilih 1.Tambah Produk di Awal maka user diminta untuk memasukkan kode produk, nama produk, harga produk, stok produk, dan kategori produk (dengan catatan kode produk tidak boleh sama dan tidak boleh di kosongkan, harga dan stok bersifat integer).

   ![Cuplikan layar 2024-03-02 093913](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/eae60162-08ed-4ebd-b446-0457cf24ed77)
   ![Cuplikan layar 2024-03-02 094154](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/ff0eecd7-a006-42a1-ba2a-7751fa5b7c9f)


      *2.Tambah Barang di Akhir
         Tambah barang di akhir artinya barang yang akan user tambahkan akan otomatis berada di akhir atau di paling bawah pada list barang. Jika user memilih 2.Tambah Produk di Akhir maka user diminta untuk memasukkan kode produk, nama produk, harga produk, stok produk, dan kategori produ (dengan catatan kode produk tidak boleh sama dan tidak boleh di kosongkan, harga dan stok bersifat integer).

   ![Cuplikan layar 2024-03-02 094208](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/dabd1b46-5a45-402e-8ddc-717c3ee4f4d8)
   ![Cuplikan layar 2024-03-02 094237](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/595a3ae1-d6ea-40c0-a0b5-1a8baf2a0e81)



      *3.Tambah Barang di anatara Node
         Tambah barang di antara node artinya barang yang akan user tambahkan akan otomatis berada di bawah kode barang yang di pilih. Jika user memilih 3.Tambah Produk di antara node maka user diminta untuk memasukkan kode produk setelah node baru di tambahkan,  kode produk yang ingin di tambahkan, nama produk, harga produk, stok produk, dan kategori produk (dengan catatan kode produk tidak boleh sama dan tidak boleh di kosongkan, harga dan stok bersifat integer).

   ![Cuplikan layar 2024-03-02 094333](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/3d0a451e-2a32-4e01-aa4b-1ff03035720e)


      *0.Kembali
      Jika User memilih 0.kembali maka program akan kembali kemenu utama

   ![Cuplikan layar 2024-03-02 094354](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/76dc538d-f5e3-4883-9efa-dc8a6e4dcbfe)
   ![Cuplikan layar 2024-03-02 084512](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/a05b2206-e0f4-416e-b07b-3f0d49c79070)



   -2.Lihat Daftar Produk.
      Jika user memillih 2.Tampilkan Data Produk makaa data Produk akan di tampilkan dengan menggunkana prettytable.
      
   ![Cuplikan layar 2024-03-02 094422](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/17d9ac89-bbf6-45ab-80d6-ecbeb8f5fce7)
   ![Cuplikan layar 2024-03-02 094409](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/f5737672-d555-4be4-aaf3-654cfe78ea67)

   -3.Update Produk
      Jika user memilih 3.Update Produk maka user diminta untuk memasukkan kode barang yang akan di update setelah itu masukan nama produk baru, harga produk baru, stok produk baru, dan kategori produk baru (dengan catatan kode barang tidak dapat di ubah dan jika tidak ingin mengubah bisa di kosongkan).
      
   ![Cuplikan layar 2024-03-02 094433](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/8716e135-2e89-4fe8-b55c-9bee8c5d9196)
   ![Cuplikan layar 2024-03-02 094526](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/6e52e2bd-9169-4306-bc00-f770e060d3f2)


   -4.Delete Produk
      Jika user memilih4.Delet Produk maka user akan di tampilkan 4 menu delete yaitu 1.Delete Produk di Awal, 2.Delete Produk di Akhir,3.Delete Produk di antara node, dan 0.Kembali

   ![Cuplikan layar 2024-03-02 094540](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/1a4e9f07-4457-4dca-b070-58f16231c985)


      *1.Delete Produk di Awal.
      ini artinya jika user memilih 1.Delete Produk di Awal maka kode produk paling atas atau paling awal akan terhapus tanpa user memasukkan kode produknya.

   ![Cuplikan layar 2024-03-02 094552](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/4d045a49-f274-4ecf-9f49-d5eb43da4d5c)
   ![Cuplikan layar 2024-03-02 094622](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/a7530c68-0c00-48d1-9cfb-8a5a8d59d3cc)

      *2. Delete Produk di Akhir.
      ini artinya jika user memilih 2.Delete Produk di Akhir maka kode produk paling bawah atau paling terkahir akan terhapus tanpa user memasukkan kod produknya.

      ![Cuplikan layar 2024-03-02 094641](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/2c708128-ab5e-4b61-abb1-3fbba4d795b5)


     *3.Delete Produk di antara Node
      ini artinya jika user memilih 3.Delete Produk di antara Node maka user diminta untuk memasukkan kode produk di atas node yang ingin di hapus.
      
      ![Cuplikan layar 2024-03-02 094711](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/97c5c3c4-45d5-4aa0-bf83-d902c156bb15)



      *0.Kembali
      jika user memilih 0.kembali makan akan kembali ketampilan menu utama.

      ![Cuplikan layar 2024-03-02 094721](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/26b34c11-9603-4ea1-86a8-7adb47853bde)
      ![Cuplikan layar 2024-03-02 084512](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/ac99b0ad-3c98-42c0-8ff0-4bbc03a0a1d2)



3. Tampilan Akhir Program
   
   -0.Keluar
   Jika User memilih 0.keluar maka program akan berhenti.

![Cuplikan layar 2024-03-02 094731](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/9f4bdf77-0b67-4449-8c7b-d3ccdb279af8)
![Cuplikan layar 2024-03-02 094740](https://github.com/nyomanarinit/MP1_MTokoKosmetik/assets/145880551/7e823d3e-427c-421f-80a1-6b0f3d63e68f)


## MP3_MTokoKosmetik
### Penjelasan dan Output Program.

~ Tampilan Tambahan Sorting Produk

![Cuplikan layar 2024-03-10 094252](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/34ff975c-ed80-4ead-a36d-e4ff58d69971)

->Tampilan Menu awal ditambahkan pilihan 5. Sorting.

![Cuplikan layar 2024-03-10 094300](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/ac668d94-3075-46b1-8d37-091ab2d02ae2)

![Cuplikan layar 2024-03-10 094314](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/324c94e7-2b5a-4a67-89ba-d2cdd60bb231)

jika memilih 5.sorting maka akan ditampilkan 3 pilihan yaitu 1.Sorting berdasarkan kode, 2.shorting berdasarkan nama dan 0. Kembali ke menu utama.


->Tampilan Shorting

![Cuplikan layar 2024-03-10 094321](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/8810cbf6-4670-46b9-aae4-4fe01d6018e3)

![Cuplikan layar 2024-03-10 094343](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/add1e1b3-70f9-496a-ad4b-9184e3af3537)

![Cuplikan layar 2024-03-10 094402](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/0da6e870-2f5f-43d6-a74e-432b881b2dcf)


tampilan sorting berdasarkan kode barang setelah memilih 1.soting berdasarkan kode barang user dapat memilih apakah ingin di sorting secara ascending atau discanding jika ascanding ketikan asc jika discanding ketikan desc.


![Cuplikan layar 2024-03-10 094412](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/efec654b-1952-453d-a5a8-dbd9fff224da)

![Cuplikan layar 2024-03-10 094426](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/e39b4813-caf9-4241-9cc3-f02373b77b9b)

![Cuplikan layar 2024-03-10 094438](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/5cae30f6-b785-49ce-a649-51195bd84975)


tampilan sorting berdarakan nama jika user memilih sorting berdasarkan nama maka user di minta untuk memilih ingin sorting barang atau produk secara ascending atau discanding jika ascanding ketikan asc jika discanding ketikan desc.

->Tampilan kembali kemenu utama

![Cuplikan layar 2024-03-10 095230](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/da52d6fc-da46-4242-93d1-ac43a69998b6)

![Cuplikan layar 2024-03-10 095220](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/5c50e745-a645-421e-b827-5cb98ae82fe5)

dan jika user memilih 0.kembali kemenu utama maka program akan menampilkan kembali kemenu utama.

## MP4_MTokoKosmetik
### Penjelasan dan Output Program.

1. Tampilan Menu Utama
   pada tampilan utama ini saya menambahkan searching. searching saya letakkan setelah melakukan shorting 

![Cuplikan layar 2024-03-17 094141](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/1d628983-b5e5-4076-bac6-19b7e9853be5)


2. Tampilan Searching

![Cuplikan layar 2024-03-17 094208](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/a5533aa1-6879-4504-936e-2ccbf8c3def1)
![Cuplikan layar 2024-03-17 094221](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/9482edec-78b6-4c98-875b-31d495d15217)
![Cuplikan layar 2024-03-17 094243](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/cce51174-32fd-4dcc-a3f4-66ed72fbe878)
![Cuplikan layar 2024-03-17 094256](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/d80fe0b9-3d71-461a-8b48-eaf759addd77)

user diminta untuk melakukan shorting dulu setelah itu bisa melakukan searching, di sini saya menerapkan searching dengan metode jump search.

3. Tampilan Kembali
jika user memilih 0. maka akan kembali ke menu shorting

![Cuplikan layar 2024-03-17 094310](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/821465e5-a895-4dad-958e-c6e5e46be9c0)
![Cuplikan layar 2024-03-17 094315](https://github.com/nyomanarinit/MP_MTokoKosmetik/assets/145880551/9beb6ca9-8dbd-4b01-b23f-c52792d1c50f)









