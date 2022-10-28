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
* Dari berbagi macam kategori, kategori yang paling banyak diminati adalah `Entertainment`, `Music`, dan `Howto and Style`, hal ini dapat dilihat dari jumlah video yang masuk pada list trending. Ketiga kategori diatas memiliki jumlah video paling banyak (Top 3).
* Konsistensi konten kreator dalam mengunggah video menjadi salah satu faktor masuknya sebuah channel ke dalam trending list, hal ini dapat dilihat dari channel `ESPN` yang mengunggah 83 video dari 205 hari trending. 
* Video dengan kategori music menjadi video dengan views dan likes tertingi, hal tersebut wajar karena music cenderung diputar berulang kali daripada video kategori lain.
* Durasi menjadi faktor yang pentin dalam pembuatan video. 
* Tags menjadi salah satu faktor pada video yang dapat menambah peluang video masuk pada trending list, ada tidaknya tags menjadi pembeda pada dataset ini. Video dengan tags memiliki nilai median views lebih tinggi daripada yang tidak.
* Interaction (Active User) juga menjadi salah satu hal yang perlu diperhatikan ketika menjadi konten kreator, tingginya interaction memengaruhi sebuah video untuk masuk ke dalam trending list. 
* Rasio likes punya pengaruh terhadap peluang sebuah video masuk ke trending list, rasio likes juga membuktikan bahwa views tinggi tidak menjamin sebuah video masuk list trending.
* Views dan likes punya nilai korelasi yang tinggi. 
* Hari Jumat, Kamis, Selasa dan Rabu menjadi hari terbanyak dimana konten kreator menguplod video mereka, dan pada pukul 15.00 - 17.00 menjadi waktu yang didominasi oleh video yang masuk pada trending list.
* Waktu yang dibutuhkan video baru untuk masuk trending sekitar 0 sampai 3 hari, meskipun masuk trending video tidak terbatas pada umur video.

Berikut merupakan karakteristik video yang masuk pada trending list:
* Video memiliki cakupan yang luas seperti pada kategori `Entertainment`, `Music`, dan `Howto and Style`.
* Umumnya video di unggah secara konsisten.
* Penentuan durasi harus sesuai dengan tema atau kategori video.
* Memunculkan Tags atau Keyword yang relevan. 
* Punya nilai median interaction ratio sekitar 0.3%. 
* Punya nilai median likes ratio sekitar 2.87%. 


# Rekomendasi 

1. Tentukan audience atau target market kita dalam membuat konten. Riset ini dapat dilakukan untuk mengetahui apa yang disukai oleh audience yang kita suka, dengan riset kita tidak perlu coba-coba dalam membuat konten.
2. Pembuatan video bisa diawali dengan riset terkait tema video yang akan dibuat. Penentuan tema atau kategori video berhubungan dengan durasi video yang akan dibuat. 
3. Membuat atau mengunggah video secara konsisten, konsistensi ini yang membuat seorang konten kreator atau sebuah channel dapat dikenal atau memiliki market tersendiri. 
4. Buat video atau konten yang memungkinkan user/penonton berinteraksi di kolom komentar, tidak harus ajakan eksplisit untuk berkomentar di kolom komentar, bisa juga dengan video yang punya daya tarik tersendiri agar setiap orng yang menonton mau berkomentar di kolom komentar. Usahakan yang mengandung konten positif. 
5. Penggunaan SEO untuk optimaliasi traffic di video, SEO ini digunakan untuk membantu memunculkan video paling atas ketika ada user melakukan pencarian. Hal ini dapat meningkatkan peluang video kita dapat ditonton oleh user. Berikut merupakan list yang dapat dilakukan dalam SEO:
    * Riset Keyword : Usahakan memerhatikan keyword yang sesuai dengan tema video kita dan punya volume pencarian yang tinggi. 
    * Gunakan judul/title yang sesuai dengan tema video, usahakan gunakan thumbnail yang menarik. 
    * Pasang keyword yang sudah ditentukan dalam deskripsi video.
    * Gunakan tags yang sesuai dengan judul, tema dan deksripsi video yang akan dibuat. Berdasarkan data jumlah tags yang direkomendasikan tags yang dapat di buat kurang lebih 19 tags.
    * Promosikan video secepat mungkin, lakukan promosi di platform social media lain. Dapat dilakukan dengan membuat short video atau share link pada social media lain. Karena berdasarkan data, mayoritas video yang trending adalah video-video yang cenderung sangat baru. Kepecatan penambahan views inilah yang juga dapat membuat video kita masuk dalam trending list.
6. Tentukan Hari dan Jam upload video yang efektif, berdasarkan data jam yang baik untuk mengunggah video adalah hari Jumat dan estimasi jam 15.00 - 17.00.
