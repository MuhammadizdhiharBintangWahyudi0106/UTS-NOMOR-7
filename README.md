# UTS-NOMOR-7
UTS Jawaban No 7
def kategori_usia(usia):
    batasan = [12, 18, 60]
    kategori = ["Anak-anak", "Remaja", "Dewasa", "Lansia"]

    for i, batas in enumerate(batasan):
        if usia < batas:
            return kategori[i]
    return kategori[-1]

# Contoh penggunaan
usia = 7
print(kategori_usia(usia))

Penjelasan Logika:
Kita gunakan list batasan untuk mewakili batas usia kategori.
List kategori berisi label yang sesuai.
Perulangan for dengan enumerate memeriksa apakah usia lebih kecil dari batas tertentu, dan langsung mengembalikan kategori yang sesuai.
Jika tidak memenuhi kondisi apa pun, berarti dia masuk kategori terakhir: "Lansia".
