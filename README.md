# ⚽ Post Test 1 - PBO  
## Manajemen Transfer Pemain Sepak Bola (CRUD)

---

## 👤 Data Diri  
- **Nama** : Husaini Iyastama H. 
- **NIM** : 2409116038  
- **Kelas** : A  

---

## 📖 Deskripsi Singkat  
Program ini merupakan implementasi sederhana dari sistem **CRUD (Create, Read, Update, Delete)** menggunakan bahasa pemrograman **Java**.  
Tema yang digunakan adalah **Manajemen Transfer Pemain Sepak Bola**, di mana pengguna dapat menambahkan, melihat, memperbarui, dan menghapus data transfer pemain.

Data transfer yang dikelola terdiri dari:
1. Nama Pemain  
2. Asal Tim  
3. Klub Tujuan  
4. Biaya Transfer (dalam juta euro)  

Program dibuat hanya dalam satu class **Main.java**, menggunakan **ArrayList** untuk menyimpan data transfer, serta menerapkan **percabangan (if-else)** dan **perulangan (do-while & for)** sehingga program berjalan interaktif sampai pengguna memilih menu keluar.

---

## 🔄 Alur Program  

### 1️⃣ Saat dijalankan, program menampilkan menu utama:
<img width="467" height="165" alt="image" src="https://github.com/user-attachments/assets/6bd717e0-1d5d-422c-9c54-2ec6b6e69f5b" />


- **Tambah Data Transfer** → pengguna dapat menambahkan nama pemain, asal tim, klub tujuan, dan biaya transfer.  
- **Lihat Daftar Transfer** → menampilkan seluruh data transfer yang tersimpan. Jika kosong, muncul pesan *"Belum ada data transfer."*  
- **Ubah Data Transfer** → pengguna memilih nomor transfer untuk diperbarui. Jika daftar kosong atau nomor tidak valid, muncul pesan *"Nomor tidak valid."*  
- **Hapus Data Transfer** → pengguna memilih nomor transfer untuk dihapus. Jika daftar kosong atau nomor tidak valid, muncul pesan *"Nomor tidak valid."*  
- **Keluar** → menghentikan program dengan pesan *"Keluar dari program..."*  

---

### 2️⃣ Data transfer disimpan dalam **empat ArrayList**:
- `pemain` → menyimpan nama pemain  
- `asalTim` → menyimpan asal tim  
- `klubTujuan` → menyimpan klub tujuan  
- `biayaTransfer` → menyimpan biaya transfer  

---

### 3️⃣ Program berjalan terus dengan perulangan **do-while**, sehingga tidak berhenti kecuali pengguna memilih menu **5 (Keluar)**.  

---

### 4️⃣ Menampilkan daftar transfer menggunakan perulangan **for** yang membaca semua elemen di dalam ArrayList.  

---

## 🖼️ Contoh Output  

### Menu Utama  

<img width="462" height="148" alt="image" src="https://github.com/user-attachments/assets/9db6dd9e-2835-436b-9392-440ada7689dd" />

### Tambah Data Transfer  

<img width="428" height="130" alt="image" src="https://github.com/user-attachments/assets/5b1558c5-4748-4889-b0c7-a84f27fe9a14" />

### Lihat Daftar Transfer  

<img width="522" height="102" alt="image" src="https://github.com/user-attachments/assets/f745350d-5836-41fe-9f93-aa70544e3c22" />

---

✨ Dengan demikian, program ini sudah memenuhi semua ketentuan Post Test:  
- CRUD lengkap (Create, Read, Update, Delete)  
- Menggunakan `ArrayList`  
- Semua kode ada dalam `psvm`  
- Percabangan `if-else` untuk menu  
- Perulangan `do-while` agar interaktif  
- Perulangan `for` untuk menampilkan data  








