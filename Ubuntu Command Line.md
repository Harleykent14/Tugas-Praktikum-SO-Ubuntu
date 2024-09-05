Buat 50 command line di ubuntu


command line :

![2](https://github.com/user-attachments/assets/a9b8ed12-811a-4aa6-b485-5cdb762c2842)


1. mkdir ~/contoh ( membuat direktori bernama "contoh" )


2. cd ~/contoh ( masuk ke dalam direktori )


3. touch file1.txt ( membuat file kosong bernama "file1.txt" di dalam direktori 


4. echo "ini adalah saya" > file2.txt ( menulis "ini adalah saya" di dalam file1.txt


5. mkdir subdir ( membuat subdirektori bernama "subdir" di dalam direktori )


6. cd subdir ( masuk ke dalam subdirektori bernama "subdir" )


7. touch file2.txt ( membuat file kosong bernama "file2.txt" di dalam subdirektori )


8. echo "ini file saya" > file2.txt ( menulis "ini file saya" di dalam file2.txt )


9. cp file2.txt ~/contoh/ ( menyalin "file2.txt" ke dalam direktori "contoh" ) 


10. mv file2.txt ~/contoh/ ( memindahkan "file2.txt" ke dalam direktori "contoh" )


11. cd.. ( kembali satu tingkat dari direktori yang dibuka sekarang )


12. ls ( Menampilkan daftar file dan direktori di dalam direktori saat ini )


13. rm -r subdir ( menghapus subdirektori "subdir" beserta isinya )


14. touch file3.txt ( membuat file kosong bernama "file2.txt" )


15. cat file1.txt > file3.txt ( membaca dan menampilkan isi dari "file1.txt" )


16. echo "mahasiswa UNSRI" >> file3.txt (  menambahkan teks "mahasiswa UNSRI" ke akhir file file3.txt )


17 head file3.txt ( membaca dan menampilkan bagian awal dari "file3.txt: )


18. tail file3.txt ( membaca dan menampilkan bagian akhir dari "file3.txt" )


19. grep "UNSRI" file3.txt ( mencari baris yang berisi "UNSRI" di semua sistem )


![3](https://github.com/user-attachments/assets/7fb508ff-b045-4c65-a25f-2ff2cb7e507e)


20. chmod 755 file3.txt ( mengatur izin akses file "file3.txt" )

21. chmod644 file3.txt ( mengubah izin akses file "file3.txt" )


22. mkdir -p dir1/dir2/dir3/dir4 ( membuat direktori "dir1/dir2/dir3/dir4" secara berurutan )


23. touch dir^c ( mencoba membuat file direktori namun gagal )


24. touch dir1/dir2/dir3/dir4/file4.txt ( membuat file kosong bernama "file4.txt" di dalam direktori "dir1/dir2/dir3/dir4" )


25. cp dir1/dir2/dir3/dir4/file4.txt dir1/ ( menyalin "dir1/dir2/dir3/dir4/file4.txt" ke direktori "dir1" )


26. mv dir1/dir2/dir3/dir4/file4.txt dir1/ ( memindahkan "dir1/dir2/dir3/dir4/file4.txt" ke direktori "dir1" )


27. rm dir1/dir2/dir3/dir4/file4.txt ( Mencoba menghapus direktori dir1/dir2/dir3/dir4/file4.txt (gagal karena folder tidak kosong))


28. rm -r dir1 (  menghapus direktori "dir1" beserta isinya )


29. touch file5.txt file6.txt file7.txt ( membuat file kosong "file5.txt file6.txt file7.txt" secara beruntun)


30. ls -1 ( Menampilkan daftar file dengan informasi yang lebih lengkap )


31. df -h ( Menampilkan penggunaan disk dengan format yang mudah dibaca )


32. du -sh ( Menampilkan ukuran direktori saat ini )


![4](https://github.com/user-attachments/assets/d1e6d7de-e3ac-48ca-a4db-12e71e4c8dca)


33. find . -name "*.txt ( mencari semua file dengan ekstensi ".txt" )


34. locate file1.txt


35. grep -r "ini"


36. tar -cvf archive.tar file1.txt file3.txt ( membuat arsip "archive.tar" yang berisi file1.txt file3.txt )


37. tar -xvf archive.tar ( mengestrak isi dari "archive.tar" )


38. gzip archive.tar ( mengompres "archive.tar" menjadi archive.tar.gz )


39. gunzip archive.tar.gz ( mengestrak "archive.tar.gz" kembali menjadi "archive.tar." )


40. zip archive, zip file1.txt file3.txt (


41. unzip archive.zip


![5](https://github.com/user-attachments/assets/18820858-5aa0-49a2-bdde-2b5e33e77f9c)


42. ps aux ( menampilkan semua proses yang sedang berjalan )


43. top ( Menampilkan informasi proses secara real-time )


![7](https://github.com/user-attachments/assets/45d08807-91b3-4932-8f72-7951bbfc799a)


44. swapon --show


45. ip add


46. ifconfig ( Menampilkan informasi jaringan )


47. sudo adduser guest 


![8](https://github.com/user-attachments/assets/8e9cdb70-0980-4dc3-a21b-1e139c886542)


48. lsb_release -a


49. pwd ( Menampilkan direktori kerja saat ini )


50. clear ( membersihkan semua sistem di terminal )

































