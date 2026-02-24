
# 🛒 Tugas PAB - Eksperimen Part 5  
## EKSPERIMEN 5: Test Cart Operations  

**Nama  : Tsabitah Kawiswara**  
**NIM   : 2409116099**

**Kelas : Sistem Informasi C**

---

## 1️⃣ Add Product 3x → Quantity Should Be 3 ✓  

<img width="961" height="533" alt="Cart View" src="https://github.com/user-attachments/assets/5eba690d-fd4c-427e-b635-fb6b64e59814" />

Pada pengujian ini, produk **Laptop Gaming** ditambahkan sebanyak **3 kali** ke dalam keranjang.

Harga satuan: **Rp 15.000.000**  
Total yang dihasilkan:

> Rp 15.000.000 × 3 = **Rp 45.000.000**

✅ Tombol tambah dan kurang berfungsi dengan baik  
✅ Quantity bertambah sesuai input  
✅ Total harga terupdate secara otomatis  

Hal ini membuktikan bahwa sistem berhasil mengelola penambahan produk dan perhitungan total secara akurat.

---

## Checkout → Data Summary Validation ✓  

<img width="957" height="523" alt="Checkout Dialog" src="https://github.com/user-attachments/assets/65639a28-68cf-46f5-9dc3-1cb000867013" />

Saat tombol **Checkout** ditekan, sistem menampilkan dialog konfirmasi berisi:

- Total harga sesuai dengan isi keranjang  
- Jumlah item sesuai dengan quantity sebelumnya  

✅ Data pada dialog identik dengan data cart  
✅ Tidak terdapat selisih perhitungan  

Proses validasi checkout berjalan dengan benar.

---

## 2️⃣ Tambah Produk Berbeda → Badge Menampilkan Total Produk ✓  

### 📸 Tampilan Cart dengan Produk Berbeda  

<img width="967" height="563" alt="image" src="https://github.com/user-attachments/assets/31bbe52c-c4f4-44b4-a9fe-3b07e5fb61ee" />

Tiga produk berbeda berhasil ditambahkan:

- Wireless Headphones (1 item)  
- Camera DSLR (1 item)  
- Smart Watch (1 item)  

Total harga otomatis menjadi: **Rp 16.500.000**

✅ Sistem mampu menangani lebih dari satu jenis produk  
✅ Total harga dihitung dari seluruh item berbeda  
✅ Badge menampilkan jumlah total produk (3 item)

---

### 📸 Tampilan Badge pada Halaman Products  

<img width="905" height="494" alt="image" src="https://github.com/user-attachments/assets/66416c6c-f64c-44f4-bbf9-cc2cf94d04a7" />

Pada gambar di atas terlihat halaman **Products** dengan ikon keranjang di pojok kanan atas yang menampilkan badge berwarna merah dengan angka **3**.

Angka tersebut menunjukkan bahwa terdapat **3 item di dalam cart**.

Hal ini membuktikan bahwa:

- Badge berhasil menampilkan jumlah produk secara real-time  
- Jumlah pada badge sesuai dengan total item yang telah ditambahkan sebelumnya  
- Data cart tetap sinkron meskipun pengguna berada di halaman Products  

Dengan demikian, fitur **Navigate Back → Badge Still Correct** berjalan dengan baik karena jumlah item tetap akurat setelah perpindahan halaman.

---

## 3️⃣ Increase Quantity → Updates Price ✓  

### 📸 Sebelum Quantity Ditambah  

<img width="963" height="536" alt="image" src="https://github.com/user-attachments/assets/70fa0895-a374-4e61-972d-935a5296a19f" />

Kondisi awal:

- Wireless Headphones: 1 item (Rp 1.500.000)  
- Smart Watch: 1 item (Rp 3.000.000)  
- Total: Rp 4.500.000  

Perhitungan awal sudah sesuai.

---

### 📸 Setelah Quantity Ditambah  

<img width="962" height="532" alt="image" src="https://github.com/user-attachments/assets/6b78cc51-01c8-4d9e-bbd9-eae592a5ae6c" />

Quantity Wireless Headphones ditambah dari 1 menjadi 3.

Perubahan yang terjadi:

- Harga produk: Rp 4.500.000 (1.500.000 × 3)  
- Total keseluruhan: Rp 7.500.000  

✅ Harga produk terupdate otomatis  
✅ Total keseluruhan ikut berubah  
✅ Tidak terjadi error perhitungan  

Sistem berhasil melakukan update secara real-time.

---

## 4️⃣ Decrease to 1 → Still in Cart ✓  

### 📸 Sebelum Quantity Dikurangi  

<img width="967" height="538" alt="image" src="https://github.com/user-attachments/assets/e1243c4e-99c2-4f80-82cf-d81369adcff5" />

Wireless Headphones memiliki quantity 2 dengan total Rp 3.000.000.

---

### 📸 Setelah Quantity Dikurangi Menjadi 1  

<img width="965" height="530" alt="image" src="https://github.com/user-attachments/assets/216ce80c-1066-4dcb-bf60-ef50095072a0" />

Setelah dikurangi menjadi 1:

- Total harga berubah menjadi Rp 1.500.000  
- Produk tetap tampil di dalam cart  

✅ Item tidak terhapus karena quantity > 0  
✅ Sistem hanya memperbarui nilai quantity dan total  

---

## 5️⃣ Decrease to 0 → Removed from Cart ✓  

### 📸 Sebelum Quantity Menjadi 0  

<img width="963" height="537" alt="image" src="https://github.com/user-attachments/assets/f50d253f-012c-49d7-a749-e0f5ddb6c8ba" />

Produk masih memiliki quantity 1.

---

### 📸 Setelah Quantity Menjadi 0  

<img width="960" height="532" alt="image" src="https://github.com/user-attachments/assets/81286eb5-5168-4c09-83d6-e10497d30bfb" />

Setelah quantity dikurangi hingga 0:

✅ Produk otomatis terhapus dari cart  
✅ Total harga diperbarui  
✅ Tidak ada data tersisa pada item tersebut  

Eksperimen **Decrease to 0 → Removed from Cart** berhasil.

---

## 6️⃣ Clear All → Empty Cart Message ✓  

<img width="960" height="532" alt="image" src="https://github.com/user-attachments/assets/81286eb5-5168-4c09-83d6-e10497d30bfb" />

Setelah seluruh produk dihapus, sistem menampilkan pesan:

> **"Your cart is empty"**

Disertai tombol **Continue Shopping**.

✅ Sistem mendeteksi kondisi cart kosong  
✅ Pesan ditampilkan dengan benar  
✅ User tetap dapat kembali berbelanja  

Eksperimen Clear All berhasil.

---

## 7️⃣ Navigate Back → Badge Still Correct ✓  

<img width="677" height="534" alt="image" src="https://github.com/user-attachments/assets/ad0c2b45-9c40-405f-be15-fd6e6e7401cf" />

<img width="680" height="532" alt="image" src="https://github.com/user-attachments/assets/bad8efe4-e252-46ef-803e-d31e223c9bce" />

Setelah melakukan navigasi kembali (back):

✅ Badge pada ikon cart tetap menampilkan jumlah item yang benar  
✅ Data cart tidak ter-reset  
✅ State tetap konsisten antar halaman  

Hal ini menunjukkan bahwa **state management aplikasi berjalan dengan baik dan stabil**.

---

# ✅ Kesimpulan

Seluruh pengujian pada fitur cart berhasil dijalankan dengan baik, meliputi:

- Penambahan produk  
- Pengurangan quantity  
- Penghapusan otomatis saat quantity 0  
- Validasi checkout  
- Sinkronisasi badge  
- Deteksi cart kosong  
- Konsistensi data saat navigasi  

Dengan demikian, fitur **Cart Operations** telah berjalan sesuai dengan skenario pengujian yang ditentukan.

