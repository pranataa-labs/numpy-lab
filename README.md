# NumPy Lab

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <a href="https://colab.research.google.com/github/pranataa-labs/numpy-lab/blob/main/belajar-numpy.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" style="height: 28px;"/>
  </a>
</p>

Repositori latihan interaktif untuk belajar komputasi numerik, manipulasi array multi-dimensi, dan aljabar linear menggunakan **NumPy** dari dasar hingga tingkat lanjut.

---

## 📌 Topik Pembelajaran

- **Pembuatan Array Dasar**: Import NumPy, Array 1D/2D/3D, Inspeksi Atribut (`ndim`, `shape`, `size`, `dtype`), `zeros`, `ones`, `empty`, `full`, `arange`, `linspace`, Bilangan Acak (`rand`, `randn`, `randint`).
- **Indeksasi, Slicing & Seleksi**: Indeksasi 1D/2D, Slicing Matriks, Boolean Indexing, Fancy Indexing, Kondisional `np.where`, Pencarian Posisi (`argwhere`, `nonzero`), Nilai Ekstrem (`argmax`, `argmin`), Pengurutan (`argsort`).
- **Manipulasi Bentuk & Struktur**: `reshape`, Meratakan Array (`ravel`, `flatten`), Transpose (`.T`), Menambah Dimensi (`newaxis`, `expand_dims`), Menghapus Dimensi (`squeeze`), Concatenation, Stacking (`vstack`, `hstack`), Splitting, `append`, `insert`, `delete`.
- **Operasi Matematika & Statistik**: Aritmatika Element-wise, Broadcasting, Universal Functions (`sqrt`, `exp`), Trigonometri (`sin`, `cos`, `tan`), Logaritma, Agregasi (`sum`, `mean`, `median`), Varians & Deviasi (`var`, `std`), Operasi Axis, Pembulatan (`round`, `ceil`, `floor`), Perkalian Matriks (`dot`, `@`).
- **Aljabar Linear & Manajemen Data**: Nilai Unik (`unique`), Operasi Himpunan (`intersect1d`, `union1d`), Penanganan NaN (`isnan`, `nanmean`), Invers Matriks (`linalg.inv`), Determinan (`linalg.det`), Eigenvalues & Eigenvectors (`linalg.eig`), Sistem Persamaan Linear (`linalg.solve`), Format Teks (`savetxt`, `loadtxt`), Format Biner (`.npy`), Manajemen Memori (*View* vs *Copy*).

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
