# Jurnal Belajar: Minggu 1

**Topik:** Pengantar Teori, Aplikasi, Regulasi, dan Etika Reverse Engineering

## Apa yang Saya Pelajari
Pada minggu pertama ini, fokus pembelajaran adalah memahami fondasi dasar dari *Reverse Engineering* (RE) sebelum masuk ke ranah teknis. Secara definisi, RE adalah proses membongkar suatu objek untuk melihat cara kerjanya, dengan tujuan mengekstrak elemen desain dan logika internal tanpa memiliki dokumentasi aslinya. Praktik ini ternyata memiliki ruang lingkup yang luas, mulai dari menganalisis *binary* (Software RE), sirkuit fisik (Hardware RE), hingga format komunikasi data (Protocol RE). 

Saya juga diperkenalkan pada area penerapannya yang sangat krusial dalam dunia keamanan siber, seperti untuk mencari kerentanan (*vulnerability research*), melakukan *penetration testing* pada aplikasi tertutup, hingga membedah kode *malware* atau ransomware untuk mengidentifikasi server *Command and Control* (C2).

## Apa yang Saya Pahami
Dari materi ini, saya kini bisa menarik garis tegas antara *Reverse Engineering* dan pembajakan (*Software Piracy*). Meskipun keduanya melibatkan proses membongkar *software*, tujuannya bertolak belakang. RE dilakukan untuk pemahaman, perbaikan, dan peningkatan sistem, sedangkan pembajakan murni untuk keuntungan komersial dari pencurian hak cipta.

Selain itu, saya memahami bahwa praktik RE diatur oleh batasan hukum dan etika yang ketat. Di Amerika Serikat, terdapat *Digital Millennium Copyright Act* (DMCA) yang melarang pembobolan kontrol akses digital, namun tetap memberikan pengecualian (izin) jika RE dilakukan untuk tujuan interoperabilitas, penelitian keamanan, atau aksesibilitas. Sebagai praktisi, mematuhi etika profesional adalah wajib dan mutlak, contohnya dengan menerapkan "Responsible Disclosure" yaitu melaporkan celah keamanan ke pihak pengembang terlebih dahulu sebelum mempublikasikannya ke publik.

## Apa yang Masih Membingungkan
Meskipun konsep teoritis dan etikanya sudah jelas, saya masih belum memiliki gambaran konkret mengenai cara kerja *tools* yang disebutkan, terutama perbedaan visual dan fungsional antara *Disassemblers* (seperti IDA Pro) yang mengubah biner ke *assembly*, dengan *Decompilers* (seperti Ghidra) yang mengubahnya ke bahasa tingkat tinggi. 

Selain itu, pada bagian tantangan RE, disebutkan tentang teknik *Obfuscation* (pengaburan kode) dan *Anti-Debugging*. Saya masih bingung bagaimana wujud dari kode yang sudah di*obfuscate*.
