langkah mengaitkan github dan folder lokal: 
[di terminal]
    cd C:path/lokasi/file 
    git remote add origin URL REPO
    git remote -v //cek status remote di folder proyek

DAILY WORKFLOW / ALUR KERJA UTAMA SEHARI-HARI
    stage changes (git add) -> TANDAI FILE MANA YANG AKAN DIUBAH
    commit (git commit)-> SIMPAT PERUBAHAN BESERTA PESAN PENJELASANNYA DI LOKAL
    push ( git push )-> KIRIM HASIL COMMIT DARI KOMPUTER LOKAL KE REPO
    status ( git status) -> CEK APA SAJA YANG TERJADI DI REPO (COMMIT,ADD,PUSH,ETC)
        -UNTRACKED FILES (MERAH) : FILE YANG BARU DIBUAT & GA DIKENAL OLEH GITHUB
        -CHANGES NOT STAGED FOR COMMIT (MERAH) : FILE LAMA YANG BARU DIEDIT DAN BELUM DI STAGE 
        -CHANGES TO BE COMMITED (HIJAU) : FILE YANG UDAH DI [git add] DAN SIAP DI-COMMIT
        -WORKING TREE CLEAN : GAK ADA PERUBAHAN, FOLDER UDAH RAPI
    pull (git pull, git pull origin) masih belum paham

    
