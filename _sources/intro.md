# Apa itu Text Mining?
Text Mining (penambangan teks) adalah proses menggali informasi atau pola tersembunyi dari kumpulan teks.
Bayangkan kita punya tumpukan buku, artikel, komentar media sosial, atau ulasan produk. Kalau dibaca satu per satu pasti capek dan lama. Nah, dengan text mining, komputer bisa membaca banyak teks sekaligus lalu menyimpulkan isinya.
________________________________________
Bagaimana Caranya?
Secara umum, langkah-langkahnya seperti ini:
## 1.	Kumpulkan teks (data)
Misalnya kumpulan ulasan pelanggan di Tokopedia, berita online, atau tweet di Twitter. Nah pada kasus ini saya mengumpulkan ulasan Pariwisata melalui Platform Google Mpas dengan 10 wisata yang ada di madura dengan rekomendasi bu Khofifah yang dapat diakses melalui link berikut https://www.detik.com/jatim/wisata/d-6692826/10-wisata-keren-madura-yang-direkomendasikan-gubernur-khofifah.
## 2.	Bersihkan teks
Teks biasanya kotor: ada tanda baca, singkatan, kata-kata tidak penting (“yang”, “dan”, “di”).
Jadi harus dibersihkan dulu biar rapi melalui preprocessing.
## 3.	Ubah teks jadi angka
Komputer hanya paham angka, jadi kata-kata diubah ke bentuk numerik (misalnya menghitung frekuensi kata).
## 4.	Analisis / cari pola
Dari data itu, kita bisa melakukan banyak hal, misalnya:

Klasifikasi → menandai apakah ulasan positif atau negatif.

    o	Clustering → mengelompokkan berita berdasarkan topik.

    o	Ekstraksi kata kunci → mencari kata yang paling sering muncul.

    o	Sentiment analysis → memahami emosi dalam teks (positif, negative, dan netral)

Contoh Sederhana

Misal ada 3 ulasan pembeli:

    •	“Produknya bagus sekali.”

    •	“Pengiriman lambat, saya kecewa.”

Dengan text mining, komputer bisa simpulkan:

    •	Kata positif: bagus, murah, oke

    •	Kata negatif: lambat

    •	Hasil: 1 ulasan positif, 1 ulasan negatif.
________________________________________
Analogi untuk Orang Awam

Text mining itu ibarat menyaring pasir untuk mencari emas.

    •	Pasir = kumpulan teks yang sangat banyak.

    •	Proses menyaring = pembersihan dan analisis teks.

    •	Emas = informasi penting (pola, sentimen, tren).

Pada kasus ini saya akan mengklasifikaskan ulasan pariwisata yang ada di madura dengan sentiment analisist


