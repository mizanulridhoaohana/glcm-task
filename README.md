<a name="readme-top"></a>
# glcm-task
Modul 8: Ekstraksi Fitur
         (Gray Level Co-occurence Matrix (GLCM))

Pada modul ini praktikan diharapkan bisa melakukan ekstraksi fitur menggunakan metode **Gray Level Co-occurence Matrix (GLCM)**.

_Untuk menjawab soal mohon ikuti langkah ini dengan seksama_

### Dataset

1. Clone repositori ini, untuk mendapatkan dataset.
   ```sh
   git clone https://github.com/mizanulridhoaohana/glcm-task
   ``` 
2. Dataset akan nampak seperti berikut:
   
   ![image](https://github.com/mizanulridhoaohana/glcm-task/assets/112617513/1e0d35a2-e174-47f4-9136-22f037843f24)
   ![image](https://github.com/mizanulridhoaohana/glcm-task/assets/112617513/b56c0158-1eda-4b7e-8601-abba766d0826)


   

### Instruksi
1. Unduh dataset.
2. Lakukan normalisasi terhadap dataset tersebut kemudian resize dataset ke ukuran 300 pixel.
3. Ekstraksilah dataset yang diberikan menggunakan sudut 0, 45, 90 dan 135. Dimana masing-masing sudut tersebut akan menghasilkan matrix baru.
4. Matrix tersebut akan diekstraksi dan menghasilkan fitur berikut:
   - [x] Kontras
   - [x] Dissimiliarity
   - [x] Homogenitas
   - [x] Entropi
   - [x] ASM
   - [x] Energy
   - [x] Correlation
 5. Buatlah korelasi fitur menggunakan Person Correlation.
 6. Tampilkanlah 5 korelasi tertinggi dari hasil korelasi fitur kalian.
 7. Analisislah perbedaan hasil ekstraksi fitur yang sudah dilakukan.

### Output
1. File .csv yang berisi fitur dataset.
2. Gambar Pearson correlation.
3. Dataset yang sudah di resize.


_Gunakanlah 100-150 record dataset per label jika dataset dirasa terlalu berat untuk dieksekusi._

_Selamat mengerjakan!!_

### Terima Kasih
