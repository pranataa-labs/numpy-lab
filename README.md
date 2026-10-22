# 🔢 NumPy Lab (75 Topik Komprehensif)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <a href="https://colab.research.google.com/github/pranataa-labs/numpy-lab/blob/main/belajar-numpy.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" style="height: 28px;"/>
  </a>
</p>

Repositori modul dan latihan interaktif komprehensif (75 topik) untuk komputasi numerik, aljabar linear tingkat lanjut, dekomposisi matriks, transformasi Fourier, dan manipulasi tensor menggunakan **NumPy** di Google Colab atau JupyterLab.

---

## 📌 Topik Pembelajaran

- **Pembuatan Array Dasar**: Import NumPy, Array 1D/2D/3D, Atribut (`ndim`, `shape`, `size`, `dtype`), `zeros`, `ones`, `empty`, `full`, `arange`, `linspace`, Bilangan Acak (`rand`, `randn`, `randint`).
- **Indeksasi, Slicing & Seleksi**: Indeksasi 1D/2D, Slicing Matriks, Boolean Indexing, Fancy Indexing, Kondisional `np.where`, Pencarian Posisi (`argwhere`, `nonzero`), Nilai Ekstrem (`argmax`, `argmin`), Pengurutan (`argsort`).
- **Manipulasi Bentuk & Struktur**: `reshape`, Meratakan Array (`ravel`, `flatten`), Transpose (`.T`), Menambah Dimensi (`newaxis`, `expand_dims`), Menghapus Dimensi (`squeeze`), Concatenation, Stacking (`vstack`, `hstack`), Splitting, `append`, `insert`, `delete`.
- **Operasi Matematika & Statistik**: Aritmatika Element-wise, Broadcasting, Universal Functions (`sqrt`, `exp`), Trigonometri (`sin`, `cos`, `tan`), Logaritma, Agregasi (`sum`, `mean`, `median`), Varians & Deviasi (`var`, `std`), Operasi Axis, Pembulatan (`round`, `ceil`, `floor`), Perkalian Matriks (`dot`, `@`).
- **Aljabar Linear & Manajemen Data**: Nilai Unik (`unique`), Operasi Himpunan (`intersect1d`, `union1d`), Penanganan NaN (`isnan`, `nanmean`), Invers Matriks (`linalg.inv`), Determinan (`linalg.det`), Eigenvalues & Eigenvectors (`linalg.eig`), Sistem Persamaan Linear (`linalg.solve`), Format Teks (`savetxt`, `loadtxt`), Format Biner (`.npy`), Manajemen Memori (*View* vs *Copy*).
- **Aljabar Linear Lanjutan & Komputasi Ilmiah**: Singular Value Decomposition (`linalg.svd`), QR Decomposition (`linalg.qr`), Cholesky Decomposition (`linalg.cholesky`), Norm Vektor & Matriks (L1, L2, Frobenius), Bilangan Kondisi Matriks (`linalg.cond`), Moore-Penrose Pseudoinverse (`linalg.pinv`), Polynomial Fitting (`np.polyfit`, `poly1d`), Fast Fourier Transform 1D (`np.fft.fft`), Histogram Numerik 1D & 2D, Cumulative Sum & Product (`cumsum`, `cumprod`), Pembatasan Nilai (`np.clip`), Trace & Diagonal Matriks, Matriks Segitiga (`triu`, `tril`), Outer Product, Kronecker Product, Notasi Einstein Summation (`np.einsum`), Masked Array (`numpy.ma`), Distribusi Statistik (Poisson, Probabilitas Berbobot), Structured Arrays (Record Array), Grid Koordinat 2D (`np.meshgrid`), Vektorisasi Fungsi (`np.vectorize`), Gradien Numerik (`np.gradient`), Interpolasi Linier 1D (`np.interp`), Operasi Bitwise.

---

## 🚀 Cara Menjalankan

### Opsi A: Google Colab
Klik badge **Open in Colab** di atas atau buka file `belajar-numpy.ipynb` langsung di Google Colab.

### Opsi B: Lokal / JupyterLab
```bash
# Clone repository
git clone https://github.com/pranataa-labs/numpy-lab.git
cd numpy-lab

# Install dependencies
pip install -r requirements.txt

# Jalankan JupyterLab
jupyter lab
```

---

<p align="center">
  Crafted with curiosity by <a href="https://github.com/pranataa-labs"><b>pranataa-labs</b></a>.
</p>
