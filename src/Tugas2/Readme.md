
## Cara Menggunakan

1. **Pilih Event**  
   Pengguna akan diminta untuk memilih event dengan memilih salah satu dari pilihan berikut:
    - 1: Event A
    - 2: Event B
    - 3: Event C

2. **Pilih Kategori Kursi**  
   Pengguna dapat memilih kategori kursi sebagai berikut:
    - 1: VVIP (Rp 1.000.000)
    - 2: VIP (Rp 500.000)
    - 3: Reguler (Rp 200.000)

3. **Masukkan Jumlah Tiket**  
   Pengguna diminta memasukkan jumlah tiket yang ingin dibeli.

4. **Pilih Makanan (Opsional)**  
   Pengguna dapat memilih untuk membeli makanan atau tidak:
    - Jika "Y" atau "y": Pengguna akan diminta memasukkan jumlah makanan yang ingin dibeli.
    - Jika "N" atau "n": Pembelian makanan dilewati.

5. **Ringkasan Pemesanan**  
   Setelah semua data dimasukkan, aplikasi akan menampilkan ringkasan pemesanan yang mencakup:
    - Nama Event
    - Kategori Kursi
    - Jumlah Tiket
    - Total Biaya

## Kelas dan Fungsinya

### MainApp
Kelas utama yang mengelola keseluruhan alur program, termasuk pengambilan input dari pengguna dan perhitungan total biaya.

### Event
Kelas yang menyimpan informasi tentang event yang dipilih pengguna.
- `setEventName(int eventChoice)`: Mengatur nama event berdasarkan pilihan.
- `getEventName()`: Mengambil nama event yang dipilih.

### Seat
Kelas yang menangani kategori kursi beserta tipe dan harga kursi.
- `setSeat(int seatChoice)`: Mengatur tipe dan harga kursi berdasarkan pilihan.
- `getSeatType()`: Mengambil tipe kursi.
- `getSeatPrice()`: Mengambil harga kursi.

### Food
Kelas untuk menyimpan jumlah makanan yang dipesan dan menghitung total biaya makanan.
- `setFoodCount(int foodCount)`: Mengatur jumlah makanan.
- `getFoodCost()`: Menghitung biaya total makanan berdasarkan jumlah yang dipesan.

## Contoh Penggunaan

Berikut adalah contoh bagaimana aplikasi akan berjalan:

