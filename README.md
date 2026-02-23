# 🛒 Tugas PAB - Eksperimen Part 5  
## EKSPERIMEN 5: Test Cart Operations

**Nama  : Tsabitah Kawiswara**  
**NIM   : 2409116099**

---

## 1️⃣ Add Product 3x → Quantity should be 3 ✓

<img width="961" height="533" alt="Cart View" src="https://github.com/user-attachments/assets/5eba690d-fd4c-427e-b635-fb6b64e59814" />

Pada gambar pertama terlihat produk **Laptop Gaming** berhasil ditambahkan sebanyak **3 item** dengan harga satuan **Rp 15.000.000**, sehingga total otomatis menjadi **Rp 45.000.000**. Tombol tambah dan kurang berfungsi dengan baik serta total harga ditampilkan sesuai, menunjukkan fitur keranjang berjalan dengan benar.

---

## Checkout → Data Summary Validation ✓

<img width="957" height="523" alt="Checkout Dialog" src="https://github.com/user-attachments/assets/65639a28-68cf-46f5-9dc3-1cb000867013" />

Pada gambar kedua, saat tombol **Checkout** ditekan, muncul dialog konfirmasi yang menampilkan total harga dan jumlah item yang sesuai dengan data di keranjang. Hal ini menunjukkan proses checkout dan pengambilan data sudah berjalan dengan tepat.

---

## 2️⃣ Tambah Produk yang Berbeda → Badge Menampilkan Total Produk ✓

### 📸 Gambar 1 – Tampilan Cart dengan Produk Berbeda

<img width="967" height="563" alt="image" src="https://github.com/user-attachments/assets/31bbe52c-c4f4-44b4-a9fe-3b07e5fb61ee" />

Pada gambar pertama terlihat tiga produk berbeda berhasil ditambahkan ke dalam keranjang, yaitu Wireless Headphones, Camera DSLR, dan Smart Watch, masing-masing sebanyak 1 item. Total harga otomatis terhitung menjadi Rp 16.500.000. Hal ini menunjukkan bahwa sistem mampu mengelola beberapa jenis produk sekaligus dan menghitung totalnya dengan benar.

---

### 📸 Gambar 2 – Validasi Saat Checkout

<img width="962" height="538" alt="image" src="https://github.com/user-attachments/assets/9d407a89-950f-4e4d-a91e-5cce1d614118" />

Pada gambar kedua, saat tombol Checkout ditekan, sistem menampilkan dialog konfirmasi dengan total harga Rp 16.500.000 dan jumlah item sebanyak 3. Jumlah item tersebut sesuai dengan total produk berbeda yang telah ditambahkan sebelumnya. Ini membuktikan bahwa badge pada ikon keranjang berhasil menampilkan total produk secara akurat.


## 4️⃣ Increase Quantity → Updates Price ✓

### 📸 Gambar 1 – Sebelum Quantity Ditambah

<img width="963" height="536" alt="image" src="https://github.com/user-attachments/assets/70fa0895-a374-4e61-972d-935a5296a19f" />


Pada gambar pertama terlihat produk Wireless Headphones memiliki quantity sebanyak 1 dengan harga Rp 1.500.000, dan Smart Watch sebanyak 1 dengan harga Rp 3.000.000. Total keseluruhan yang ditampilkan adalah Rp 4.500.000. Hal ini menunjukkan perhitungan awal sesuai dengan jumlah item yang ada di keranjang.

---

### 📸 Gambar 2 – Setelah Quantity Ditambah

<img width="962" height="532" alt="image" src="https://github.com/user-attachments/assets/6b78cc51-01c8-4d9e-bbd9-eae592a5ae6c" />


Pada gambar kedua, quantity Wireless Headphones ditambahkan dari 1 menjadi 3. Harga produk tersebut otomatis berubah menjadi Rp 4.500.000 (1.500.000 × 3), dan total keseluruhan juga ikut terupdate menjadi Rp 7.500.000. 

## 5️⃣ Decrease to 1 → Still in Cart ✓

### 📸 Gambar 1 – Sebelum Quantity Dikurangi

<img width="967" height="538" alt="image" src="https://github.com/user-attachments/assets/e1243c4e-99c2-4f80-82cf-d81369adcff5" />

Pada gambar pertama terlihat produk Wireless Headphones memiliki quantity sebanyak 2 dengan total harga Rp 3.000.000. Produk masih tampil normal di dalam keranjang dan total harga sesuai dengan jumlah item.

---

### 📸 Gambar 2 – Setelah Quantity Dikurangi Menjadi 1

<img width="965" height="530" alt="image" src="https://github.com/user-attachments/assets/216ce80c-1066-4dcb-bf60-ef50095072a0" />

Pada gambar kedua, quantity berhasil dikurangi dari 2 menjadi 1. Total harga otomatis berubah menjadi Rp 1.500.000 dan produk tetap tampil di dalam keranjang.


## 6️⃣ Decrease to 0 → Removed from Cart ✓

### 📸 Gambar 1 – Sebelum Quantity Menjadi 0

<img width="963" height="537" alt="image" src="https://github.com/user-attachments/assets/f50d253f-012c-49d7-a749-e0f5ddb6c8ba" />

Pada gambar pertama terlihat produk Wireless Headphones masih berada di dalam keranjang dengan quantity sebanyak 1 dan total harga Rp 1.500.000. Produk masih tampil normal dan belum terhapus dari cart.

---

### 📸 Gambar 2 – Setelah Quantity Menjadi 0

<img width="960" height="532" alt="image" src="https://github.com/user-attachments/assets/81286eb5-5168-4c09-83d6-e10497d30bfb" />


Pada gambar kedua, setelah quantity dikurangi hingga 0, produk secara otomatis terhapus dari keranjang. Hal ini menunjukkan bahwa sistem berhasil menghapus item ketika jumlah mencapai nol, sehingga eksperimen "Decrease to 0 → Removed from cart" telah terpenuhi.

---

## 7️⃣ Clear All → Empty Cart Message ✓

<img width="960" height="532" alt="image" src="https://github.com/user-attachments/assets/81286eb5-5168-4c09-83d6-e10497d30bfb" />

Setelah seluruh produk dihapus dari keranjang, sistem menampilkan pesan **"Your cart is empty"** beserta tombol *Continue Shopping*. Tampilan ini membuktikan bahwa sistem mampu mendeteksi kondisi keranjang kosong dan menampilkan pesan yang sesuai kepada pengguna. Dengan demikian, pengujian "Clear all → Empty cart message" juga berhasil terpenuhi.


<img width="677" height="534" alt="image" src="https://github.com/user-attachments/assets/ad0c2b45-9c40-405f-be15-fd6e6e7401cf" />

<img width="680" height="532" alt="image" src="https://github.com/user-attachments/assets/bad8efe4-e252-46ef-803e-d31e223c9bce" />







