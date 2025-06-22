# 🔍 Network Intrusion Detection System (NIDS) – UNSW-NB15 Dataset

Proyek ini merupakan implementasi sistem deteksi intrusi jaringan (NIDS) berbasis pembelajaran mesin menggunakan **UNSW-NB15**, salah satu dataset benchmark terbaru di bidang cybersecurity. Proyek ini bertujuan untuk mengeksplorasi data, melakukan preprocessing, serta mengembangkan model klasifikasi multiclass untuk mendeteksi berbagai jenis serangan.

---

## 📁 Dataset

- **Nama**: UNSW-NB15
- **Sumber**: [Australian Centre for Cyber Security (ACCS)](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
- **Kelas serangan**: 10 jenis (Analysis, Backdoor, DoS, Exploits, Fuzzers, Generic, Normal, Reconnaissance, Shellcode, Worms.)
- **Ukuran**: 257673 rows × 45 columns
The details of the UNSW-NB15 dataset were published in following the papers. For the academic/public use of this dataset, the authors have to cities the following papers:

- Moustafa, Nour, and Jill Slay. "UNSW-NB15: a comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set)." Military Communications and Information Systems Conference (MilCIS), 2015. IEEE, 2015.
  https://ieeexplore.ieee.org/abstract/document/7348942
- Moustafa, Nour, and Jill Slay. "The evaluation of Network Anomaly Detection Systems: Statistical analysis of the UNSW-NB15 dataset and the comparison with the KDD99 dataset." Information Security Journal: A  -Global Perspective (2016): 1-14.
  https://www.tandfonline.com/doi/abs/10.1080/19393555.2015.1125974
- Moustafa, Nour, et al. "Novel geometric area analysis technique for anomaly detection using trapezoidal area estimation on large-scale networks." IEEE Transactions on Big Data (2017).
  https://ieeexplore.ieee.org/abstract/document/7948715
- Moustafa, Nour, et al. "Big data analytics for intrusion detection system: statistical decision-making using finite dirichlet mixture models." Data Analytics and Decision Support for Cybersecurity. Springer, Cham, 2017. 127-156.
  https://link.springer.com/chapter/10.1007/978-3-319-59439-2_5
- Sarhan, Mohanad, Siamak Layeghy, Nour Moustafa, and Marius Portmann. NetFlow Datasets for Machine Learning-Based Network Intrusion Detection Systems.
  https://arxiv.org/abs/2011.09144. In Big Data Technologies and Applications: 10th EAI International Conference, BDTA 2020, and 13th EAI International Conference on Wireless Internet, WiCON 2020, Virtual Event, December 11, 2020, Proceedings (p. 117). Springer Nature.https://link.springer.com/chapter/10.1007/978-3-030-72802-1_9
---

## 📊 Eksplorasi Data (EDA)

Notebook `EDA_UNSW-NB15_Multiclass.ipynb` mencakup:
- Statistik deskriptif
- Distribusi label
- Visualisasi fitur penting
- Korelasi fitur dan heatmap
- Penanganan imbalance data (jika diperlukan)
- Comparison model

---

## ⚙️ Teknologi & Library

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📂 Struktur Folder

