Berikut adalah beberapa perintah dasar yang sering digunakan dalam membuat script Bash:

1. **echo**: Digunakan untuk mencetak teks ke terminal atau output standar.
   Contoh: 
   ```bash
   echo "Halo, dunia!"
   ```

2. **read**: Mengambil input dari pengguna dan menyimpannya ke dalam variabel.
   Contoh:
   ```bash
   echo "Masukkan nama Anda:"
   read nama
   echo "Halo, $nama!"
   ```

3. **variabel**: Variabel digunakan untuk menyimpan nilai yang dapat digunakan nanti dalam skrip. Variabel didefinisikan tanpa tanda dolar `$`.
   Contoh:
   ```bash
   pesan="Halo, dunia!"
   echo $pesan
   ```

4. **if**: Digunakan untuk melakukan percabangan berdasarkan kondisi tertentu.
   Contoh:
   ```bash
   umur=20
   if [ $umur -ge 18 ]; then
       echo "Anda sudah dewasa."
   else
       echo "Anda masih di bawah umur."
   fi
   ```

5. **for**: Digunakan untuk melakukan perulangan sejumlah tertentu.
   Contoh:
   ```bash
   for i in {1..5}; do
       echo "Perulangan ke-$i"
   done
   ```

6. **while**: Digunakan untuk melakukan perulangan selama kondisi tertentu terpenuhi.
   Contoh:
   ```bash
   angka=1
   while [ $angka -le 5 ]; do
       echo "Angka: $angka"
       ((angka++))
   done
   ```

7. **fungsi**: Anda dapat mendefinisikan fungsi dalam skrip Bash untuk melakukan tugas-tugas tertentu secara terpisah.
   Contoh:
   ```bash
   function sapa {
       echo "Halo, $1!"
   }
   sapa "John"
   ```

8. **perintah eksternal**: Anda dapat menggunakan perintah eksternal seperti `ls`, `cat`, `grep`, `awk`, dan lainnya dalam skrip Bash untuk melakukan berbagai tugas seperti manajemen file, pengolahan teks, dll.
   Contoh:
   ```bash
   files=$(ls *.txt)
   echo "Daftar file teks:"
   echo "$files"
   ```

Ini adalah beberapa perintah dasar yang sering digunakan dalam membuat script Bash. Dengan menggunakan kombinasi perintah-perintah ini, Anda bisa membuat skrip yang kompleks dan berguna untuk memenuhi kebutuhan Anda dalam otomatisasi tugas-tugas sistem atau pengembangan perangkat lunak.
