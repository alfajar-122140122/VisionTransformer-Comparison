# Chest CT-Scan Lung Cancer Classification (ViT / DeiT / Swin)

Repo ini berisi eksperimen klasifikasi jenis kanker paru berbasis citra CT-Scan dada menggunakan beberapa arsitektur Vision Transformer: ViT-Tiny, DeiT-Tiny, dan Swin-Tiny.

## Dataset
Menggunakan dataset dari Kaggle: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images

Struktur folder:
```
Data/
├── train/
├── valid/
└── test/
```

## Cara Menjalankan
### Di Kaggle
1. Tambahkan dataset ke notebook.
2. Upload notebook `ViT_Comparison.ipynb`.
3. Path dataset:
BASE_DIR = "/kaggle/input/chest-ctscan-images/Data"
4. Run all.

### Lokal
1. Download & ekstrak dataset.
2. Install dependensi:
pip install torch torchvision timm scikit-learn pandas matplotlib
3. Ubah BASE_DIR sesuai lokasi dataset.
4. Jalankan notebook melalui Jupyter.

## Output
- comparison_deit_swin.csv
- vit_tiny.pth
- deit_tiny.pth
- swin_tiny.pth

