# Molecular Dynamics of Aptamer (DNA/RNA molecules)

1. Siapkan file `Apt.pdb`.

2. Pembuatan topologi sistem simulasi.
```
gmx pdb2gmx -f Apt.pdb -o Apt_processed.gro -ignh -ter
```
Kemudian masukkan `6` dan `1` untuk memilih medan gaya AMBER dan model air TIP3P.
