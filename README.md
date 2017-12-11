# kolaborasi-tccl
Nama Anggota Kelompok

155410134 Brian duen r	(colaborator)
155410153 Hari Purnomo (colaborator)
155410121 Tyas Yanotama	(upstream)
Step by step KOLABORATOR

Pada situs github fork dulu repo yang akan dijadikan proyek bersama (repo upstream)

Clone repo hasil fork kita ke lokal menggunakan terminal. contoh perintah :

git clone https://github.com/Tyastama/kolaborasi-tccl.git
Hubungkan repo lokal dengan repo upstream dengan cara mengetikkan di terminal :
git remote add upstream https://github.com/tyastama/kolaborasi-tccl.git
Untuk mengedit file di lokal pastikan membuat branch baru terlebih dahulu sesuai issue yang ada . Menggunakan perintah :
git checkout -b tugaskolaborasitccl
Edit kode README.md program
commit kode yang telah di edit dengan mengetikan perintah sebagai berikut :

git add . git commit -m “nama commit nya”

7. Kemudian push branch kita tadi ke repo origin dengan cara :  
git push origin namabranch
Buka repository di github, lalu klik New Pull Request

Pilih opsi base fork ke master dan head form ke namabranch

Isikan keterangan lalu klik Create Pull Request

Tunggu Pull Request di Merge oleh upstream

Setelah di merge oleh upstream, pastikan branch yang berisikan commit yang telah di merge oleh upstream dihapus di github dan repo lokal.

Untuk menghapus branch pada github bisa klik Delete Branch
Untuk menghapus branch pada repo lokal dengan terminal ketikkan :
git checkout master
git branch -d namabranch
Setelah di merge oleh upstream selanjutnya samakan branch master repo lokal dengan branch master repo upstream. Dengan cara :
	git fetch upstream
	git checkout master
	git merge upstream/master
	git push origin master
Step by Step Upstream

Klik Pull Request jika ada pull request
Klik item yang ada
Jika terdapat Konflik maka klik tombol Resolve Conflicts alt tag
Edit/Hapus kode supaya tidak conflict alt tag
Selanjutnya klik Mark as Resolved jika sudah selesai editnya alt tag
Setelah itu Commit Changes
Setelah di commit , selanjutnya klik tombol Merge Pull Request untuk menggabungkan source code ke branch master alt tag
