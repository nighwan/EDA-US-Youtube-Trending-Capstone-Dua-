# EDA-US-Youtube-Trending-Capstone-Dua-
Analisis Data Trending Youtube US
# Latar Belakang

Sebuah perusahaan di bidang broadcasting dan multimedia ingin membuat lini bisnis baru demi menambah keuntungan perusahaan, salah peluang yang saat ini sedang berkembang adalah dunia digital, mengingat semua orang sudah dapat mengakses internet dari mana saja. Melihat peluang ini perusahaan memutuskan untuk masuk ke dunia Youtube guna menambah keuntungan perushaan, seperti yang kita ketahui bahwa video dengan view atau penonton yang tinggi dapat menghasilkan value, baik berupa adsense ataupun engagement rate yang dapat menarik brand maupun konten kreator lain untuk melakukan kerja sama.

# Goals

Membuat standar atau acuan bagi perusahaan dalam membuat video atau konten dengan efektif dan efisien.

# Pernyataan Masalah

Berbekal data-data yang di scraping dari youtube API, perusahaan ingin mengetahui apa saja yang harus dilakukan oleh agar dapat membuat konten-konten yang banyak diminati oleh penonton atau viewers. Karena dengan adanya analisis yang mendalam terkait konten, perusahaan tidak perlu meraba-raba dalam membuat konten yang dapat menimbulkan cost atau beban perusaahaan. Perusahaan meminta seorang data scientist untuk melakukan analisis yang mendalam terkait gambaran atau karakteristik video yang masuk dalam trending list pada data tersebut.

# Pertanyaan penelitian : Bagaimana karakteristik video Youtube yang masuk pada list trending di negara US?

# Data

Data yang digunakan dalam analisis ini hanya data list trending US selama 205 Hari, yang mana tidak dapat dibandingkan dengan data video yang tidak trending. Untuk menjawab pertanyaan perusahaan, kita akan menganalisi data history trending youtube yang sudah di scraing dari youtube API. Data yang digunakan ada dua yaitu berformat csv dan json. Untuk data dapat di akses di http: https://www.kaggle.com/datasets/datasnaek/youtube-new

# Kesimpulan
Dari analisis yang telah dilakukan kita dapat membuat kesimpulan tentang bagimana karakteristik video yang masuk pada trending list di US

Dari berbagi macam kategori, kategori yang paling banyak diminati adalah Entertainment, Music, dan Howto and Style, hal ini dapat dilihat dari jumlah video yang masuk pada list trending. Ketiga kategori diatas memiliki jumlah video paling banyak (Top 3).
Konsistensi konten kreator dalam mengunggah video menjadi salah satu faktor masuknya sebuah channel ke dalam trending list, hal ini dapat dilihat dari channel ESPN yang mengunggah 83 video dari 205 hari trending.
Video dengan kategori music menjadi video dengan views dan likes tertingi, hal tersebut wajar karena music cenderung diputar berulang kali daripada video kategori lain.
Durasi menjadi faktor yang pentin dalam pembuatan video.
Tags menjadi salah satu faktor pada video yang dapat menambah peluang video masuk pada trending list, ada tidaknya tags menjadi pembeda pada dataset ini. Video dengan tags memiliki nilai median views lebih tinggi daripada yang tidak.
Interaction (Active User) juga menjadi salah satu hal yang perlu diperhatikan ketika menjadi konten kreator, tingginya interaction memengaruhi sebuah video untuk masuk ke dalam trending list.
Rasio likes punya pengaruh terhadap peluang sebuah video masuk ke trending list, rasio likes juga membuktikan bahwa views tinggi tidak menjamin sebuah video masuk list trending.
Views dan likes punya nilai korelasi yang tinggi.
Hari Jumat, Kamis, Selasa dan Rabu menjadi hari terbanyak dimana konten kreator menguplod video mereka, dan pada pukul 15.00 - 17.00 menjadi waktu yang didominasi oleh video yang masuk pada trending list.
Waktu yang dibutuhkan video baru untuk masuk trending sekitar 0 sampai 3 hari, meskipun masuk trending video tidak terbatas pada umur video.
Berikut merupakan karakteristik video yang masuk pada trending list:

Video memiliki cakupan yang luas seperti pada kategori Entertainment, Music, dan Howto and Style.
Umumnya video di unggah secara konsisten.
Penentuan durasi harus sesuai dengan tema atau kategori video.
Memunculkan Tags atau Keyword yang relevan.
Punya nilai median interaction ratio sekitar 0.3%.
Punya nilai median likes ratio sekitar 2.87%.
