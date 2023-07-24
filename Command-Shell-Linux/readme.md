# Command Shell Linux

# command head

Perintah head melihat sepuluh baris pertama teks. Dengan menambahkan opsi, bisa mengubah jumlah baris yang ditampilkan. Command head juga digunakan untuk menampilkan data yang disalurkan (piped) ke CLI.

head [opsi] [file]

Contoh menampilkan sepuluh baris pertama file note.txt, yang terletak di direktori saat ini:

head note.txt

Berikut adalah beberapa opsi yang bisa ditambahkan:

-n atau –lines menampilkan sekian jumlah baris pertama sesuai permintaan. Misalnya, ketikkan head -n 5 namafile.txt untuk menampilkan lima baris pertama isi file namafile.txt.
-c atau –bytes menunjukkan sekian jumlah byte pertama file sesuai permintaan.
-q atau –quiet tidak akan menampilkan header yang menyebutkan nama file.

# command df
Untuk melihat penggunaan ruang disk sistem, gunakan perintah df. Hasil yang diberikan akan menggunakan persentase dan satuan KB (kilobyte). 

Berikut syntax umumnya:

df [opsi] [file]

Misalnya, masukkan perintah berikut apabila Anda ingin melihat penggunaan ruang disk sistem direktori saat ini dalam format yang mudah dipahami:

df -h

Ini beberapa opsi yang bisa digunakan dengan command df:

df -m menampilkan informasi penggunaan sistem file dalam MB.
df -k menampilkan penggunaan sistem file dalam KB.
df -T menampilkan type (jenis) sistem file dalam kolom baru.

# chgrp

perintah ini digunakan untuk merubah kepemilikan kelompok file atau direktori. Misalnya untuk memberi ijin pada kelompok atau grup agar dapat mengakses suatu file
