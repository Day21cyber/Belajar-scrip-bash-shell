Saya akan memberikan contoh sederhana untuk membuat script bash shell. Mari kita mulai dengan langkah-langkahnya:

1. **Buka teks editor**: Pertama, buka teks editor favorit Anda. Anda bisa menggunakan nano, vim, atau editor teks grafis seperti Sublime Text, Atom, atau VS Code.

2. **Mulai script**: Ketik `#!/bin/bash` di baris pertama. Ini disebut sebagai shebang, yang memberi tahu sistem bahwa file ini adalah script bash dan harus dijalankan menggunakan `/bin/bash`.

3. **Tambahkan perintah**: Tambahkan perintah-perintah yang ingin Anda jalankan dalam skrip. Misalnya, mari buat skrip sederhana yang mengucapkan "Halo, dunia!" saat dijalankan.

4. **Simpan skrip**: Simpan skrip dengan ekstensi `.sh`, misalnya `halo.sh`, agar mudah diidentifikasi sebagai skrip bash.

5. **Buat skrip dapat dijalankan**: Berikan izin eksekusi pada skrip agar bisa dijalankan. Anda bisa menggunakan perintah `chmod +x nama_skrip.sh` untuk memberikan izin tersebut.

Berikut adalah contoh sederhana skrip bash yang mengucapkan "Halo, dunia!":

```bash
#!/bin/bash

# Ini adalah komentar di dalam skrip
echo "Halo, dunia!"
```

Simpan skrip tersebut dengan nama misalnya `halo.sh`, lalu berikan izin eksekusi dengan menjalankan perintah:

```bash
chmod +x halo.sh
```

Sekarang Anda bisa menjalankan skrip dengan mengetikkan `./halo.sh` di terminal, dan itu akan mencetak "Halo, dunia!" di layar.

Ini adalah dasar pembuatan skrip bash. Anda bisa memperluasnya sesuai kebutuhan dengan menambahkan perintah-perintah yang sesuai. Jika Anda memiliki pertanyaan lebih lanjut atau ingin contoh lebih lanjut, jangan ragu untuk bertanya!
