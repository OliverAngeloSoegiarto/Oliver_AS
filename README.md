meme_dict = {
    "CRINGE": "Sesuatu yang aneh atau memalukan",
    "LOL": "Tanggapan umum terhadap sesuatu yang lucu",
    "ROFL" : "tanggapan terhadap lelucon",
    "SHEESH" : "sedikit ketidaksetujuan",
    "BTW" : "By The Way",
    "CREEPY" : "menakutkan, tidak menyenangkan",
    "AGGRO" : "menjadi agresif/marah"
    }

while True:
    word = input("Ketik kata yang tidak kamu mengerti (Gunakan hurif kapital semua!):")
    
    if word in meme_dict.keys():
        # Apa yang harus kita lakukan jika kata itu ditemukan?
        print(meme_dict[word])
    else:
        # Apa yang harus kita lakukan kata itu tidak ditemukan?
        print("Mohon maaf masih kudet")
    
