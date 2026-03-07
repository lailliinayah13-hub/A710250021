# Struktur data LIST (menyimpan beberapa nama mahasiswa)
nama_mahasiswa = ["Andi", "Budi", "Citra", "Dina"]

print("Daftar Nama Mahasiswa:")
for nama in nama_mahasiswa:
    print("-", nama)

print()

# Struktur data DICTIONARY (menyimpan nama dan nilai mahasiswa)
nilai_mahasiswa = {
    "Andi": 85,
    "Budi": 90,
    "Citra": 88,
    "Dina": 92
}

print("Nilai Mahasiswa:")
for nama, nilai in nilai_mahasiswa.items():
    print(nama, ":", nilai)

print()

# Menambahkan data baru ke LIST
nama_mahasiswa.append("Eka")
print("List setelah ditambah:", nama_mahasiswa)

# Mengubah nilai pada DICTIONARY
nilai_mahasiswa["Andi"] = 87
print("Dictionary setelah perubahan:", nilai_mahasiswa)
