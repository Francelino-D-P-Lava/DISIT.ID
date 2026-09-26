# DISIT.ID
## Distro Pakaian
### 1. Pendahuluan
      Dokumen ini mendefinisikan kebutuhan fungsional dan non-fungsional dari sistem **Marketplace Distro Pakaian DISIT.ID**, sebagai acuan bagi tim pengembang          dalam merancang, membangun, dan menguji sistem.

### 2. Kebutuhan Fungsional
      Kebutuhan fungsional mendefinisikan fitur-fitur utama yang harus disediakan oleh website penjualan pakaian distro Disit.Id.
      * [KF-01] Fitur Pencarian dan Filter
        Sistem harus menyediakan kolom pencarian produk.
        Sistem harus dapat memfilter pakaian berdasarkan model, rentang harga, dan kualitas/bahan.
      * [KF-02] Sistem Keranjang Belanja**
        Pelanggan dapat memasukkan produk ke dalam keranjang, mengubah jumlah item, atau menghapusnya sebelum melakukan *checkout*.
      * [KF-03] Sistem Pembayaran Online (Payment Gateway)**
        Website harus menyediakan sistem transaksi pembayaran online yang aman dan terintegrasi otomatis.
      * [KF-04] Notifikasi Pesanan dan Pelacakan Pengiriman**
        Sistem harus mengirimkan status pesanan secara berkala kepada pelanggan.
        Sistem harus dapat menampilkan nomor resi dan pelacakan posisi pengiriman barang.
      * [KF-05] Sistem Manajemen Inventaris (Admin Panel)**
        Pihak perusahaan (admin Disit.Id) dapat menambah, mengubah, atau menghapus stok pakaian, ukuran, warna, dan detail produk distro di gudang.

### 3. Kebutuhan Non-Fungsional (Non-Functional Requirements)
      Kebutuhan non-fungsional mendefinisikan standar kualitas, batasan teknis, dan performa dari framework programming yang diimplementasikan pada website              Disit.Id.
      * [KNF-01] Keamanan Data (Security)**
        Semua data transaksi pembayaran dan informasi pribadi pelanggan wajib dilindungi menggunakan enkripsi standar industri (seperti HTTPS dan enkripsi                 database).
      * [KNF-02] Skalabilitas Sistem (Scalability)**
        Framework dan infrastruktur website harus dirancang mampu menampung lonjakan jumlah pengguna atau trafik yang tinggi saat periode promo/diskon distro.
      * [KNF-03] Antarmuka Pengguna Responsif (Usability/UI)**
        Tampilan website harus responsif, mudah digunakan (*user-friendly*), dan nyaman diakses baik dari laptop/PC maupun dari smartphone (mobile-friendly).
      * [KNF-04] Layanan Dukungan Cepat (Support & Reliability)**
        Website harus memiliki sistem *support* atau layanan bantuan pelanggan yang responsif (misal: integrasi tombol WhatsApp atau live chat) untuk menangani            keluhan transaksi dengan cepat.

### 4. Backlog
      | No  |  Kode ID | Deskripsi Fitur / Kebutuhan                      | Prioritas   | Status | 
      | 1   |  [KF-02] | Implementasi sistem keranjang belanja dasar      |    High     |   Draft|
      | 2   |  [KF-03] | Integrasi sistem pembayaran online aman          |    High     |   Draft|
      | 3   |  [KNF-01]| Penerapan enkripsi keamanan data dan pembayaran  |    High     |   Draft|
      | 4   |  [KF-01] | Pembuatan fitur pencarian & filter baju distro   |    Medium   |   Draft|
      | 5   |  [KF-05] | Dashboard manajemen inventaris stok untuk admin  |    Medium   |   Draft|
      | 6   |  [KNF-03]| Optimasi UI/UX agar responsif di mobile          |    Medium   |   Draft|
      | 7   |  [KF-04] | Fitur sistem notifikasi & lacak resi pengiriman  |    Low      |   Draft|
      | 8   |  [KNF-04]| Integrasi sistem bantuan/support pelanggan cepat |    Low      |   Draft|

