# salafidb

Semua petunjuk ada di link website aslinya (lihat https://sites.google.com/site/salafidb/home ).
Repo ini digunakan utamanya sebagai source AUR (Arch User Repository).

بارك الله فيكم

## Catatan Sementara (untuk AUR, ada kemungkinan perubahan)

Folder `salafidb-linux4.0` harus direname menjadi `salafidb` dan ditaruh di `/usr/share/`.

File `salafidb` yang ada di dalam folder binary harus ditaruh di `/usr/bin/`.

Folder `icons` harus ditaruh di `/usr/share/` (jika ingin merge manual, gunakan `rsync`).

File `salafidb.desktop` yang ada di dalam folder `shortcut` harus ditaruh di `/usr/share/applications/`.

## TODO

Java packaging di Arch Linux memiliki aturan yang berbeda dengan AUR packages yang lainnya.
(lihat https://wiki.archlinux.org/title/Java_package_guidelines#Java_packaging_on_Arch_Linux ).
Beberapa yang perlu dilakukan sebelum submission adalah:
1. Membuat binary yang source-nya berada di `/usr/share/java/salafidb`.
2. Mengubah direktori source menjadi direktori tersebut.
3. Mengikuti petunjuk berikutnya.
