# pemweb

STEP BY STEP CARA NGECLONE

Buka git bash
Clone dengan ketik "git clone https://github.com/ratnaiswara/pemweb.git"
Kerjakan bagian masing - masing
Setelah selesai, ketik "git add . "
Lalu ketik git commit -m "apa pesan commitnya"
Terakhir, ketik git push origin master

UNTUK BUAT BRANCH

git branch nama_branch (menambah branch)
git branch (untuk melihat branch yang ada, dan melihat branch yang sedang aktif)
git checkout nama_branch (untuk berpindah branch)
pergi ke branch master lalu "git merge nama_branch"

Note : Jika terjadi conflic kita perlu menghandel nya, caranya;

buka file yang bentrok ke text editor
nanti akan terlihat hal yang bentrok dan di pisahkan dengan tanda "====="
pilih yang ingin di ambil, dan hapus yang tidak perlu
simpan dan commit perubahan git add nama_file dan git commit -m "pesan perbaikan conflic"

Note : jika branch sudah tidak aktif atau tidak ada perubahan lagi kita bisa menghapusnya caranya ;

git branch -d nama_branch

UNTUK PULL (mengambil update terbaru)

"git pull https://github.com/ratnaiswara/pemweb.git"
