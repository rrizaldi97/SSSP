# 🧮 Single-Source Shortest Path (SSSP)
**Comparative Study of Dijkstra and Bellman–Ford Algorithms**  
Kelompok 4 – Universitas Pakuan (2025)

---

## 📘 Deskripsi Proyek
Proyek ini merupakan bagian dari tugas analisis algoritma yang membandingkan **Dijkstra** dan **Bellman–Ford** dalam menyelesaikan masalah *Single-Source Shortest Path (SSSP)* pada graf berbobot positif dan campuran.  
Eksperimen dilakukan untuk mengevaluasi **kompleksitas waktu**, **efisiensi memori**, dan **ketepatan hasil** di berbagai skenario kepadatan graf.

---

## ⚙️ Algoritma yang Digunakan
1. **Dijkstra Algorithm** – Efisien untuk graf berbobot positif.  
2. **Bellman–Ford Algorithm** – Mampu menangani bobot negatif dan mendeteksi siklus negatif.  
3. **(Opsional)** Varian optimasi berbasis *priority queue* atau *heap* untuk uji kinerja tambahan.

---

## 🧪 Lingkungan dan Dependensi
Notebook ini dijalankan menggunakan:
- Python ≥ 3.10  
- Library utama:
  ```bash
  pip install numpy pandas matplotlib networkx
