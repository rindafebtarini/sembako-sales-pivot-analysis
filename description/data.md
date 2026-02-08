## Struktur Data
Berikut struktur yang digunakan:
- Order ID: Kode unik identitas pesanan
- Order Date: Tanggal dan waktu transaksi
- Customer Name: Nama pelanggan
- City: Kota lokasi pengiriman
- Product Name: Nama produk sembako dan brandnya
- Unit Price: Harga per satuan produk
- Quantity: Jumlah produk yang dibeli
- Discount (%): Persentase diskon yang diberikan
- Subtotal: Unit Price * Quantity; (Calculated)
- Discount Amount: Subtotal * (Discount / 100); (Calculated)
- Total Sales: Subtotal - Discount Amount; (Calculated)
- Shipping Fee:	Biaya pengiriman
- Grand Total: Total Sales + Shipping Fee; (Calculated)
- Payment Method:	Metode pembayaran yang digunakan
- Order Status: Status pengiriman/pesanan (Calculated)
- Platform:	Marketplace/Tempat penjualan
- Customer Rating:	Penilaian pelanggan (skala 1-5)
- Jenis Kelamin:	Gender pelanggan

Catatan: Kolom seperti Subtotal, Total Sales, Grand Total, dan Order Status merupakan data kosong karena merupakan kolom kalkulasi yang dihitung menggunakan rumus Excel.
## Catatan
Dataset tidak disertakan secara langsung dalam repository ini karena pertimbangan lisensi dan ukuran file.
