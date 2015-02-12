# Petunjuk Instalasi

##GO FOR WINDOWS

* Untuk mengunduh GO, [klik di sini](https://golang.org/dl/). Pilih versi yang sesuai dengan keinginan anda. Pilih `go1.4.1.windows-386.zip` untuk komputer 32-bit atau `go1.4.1.windows-amd64.zip` untuk komputer 64-bit.
* Buka file yang sudah didownload, lalu drag atau *extract* file ke C:
* Buka `Command Prompt` dan ketik `go` untuk memeriksa apakan Go sudah berhasil terinstal atau belum.

###Pengaturan Properties:

* Buka `File Explorer` --> klik kanan `Computer` atau `MyComputer` atau `This PC` (sesuai nama yang diberikan pada masing-masing komputer) --> klik `Properties` --> klik `Advanced system settings`
* Pada window `System Properties` pilih pengaturan `Advanced` --> klik `Environment Variables...`
* Pada window `Environment Variables` klik `New...` pada bagian `User variables for [nama komputer]`
* Pada window `New User Variable` ketikkan: `GOPATH` pada Variable name, `D:\apps\golang` pada Variable value, lalu klik `OK`.
* Klik `New...` lagi, lalu ketikkan: `GOROOT` pada Variable name, `C:\go` pada Variable value, lalu klik `OK`.
* Klik `New...` lagi, lalu ketikkan: `PATH` pada Variable name, `%GOPATH%\bin;%GOROOT%\bin` pada Variable value, lalu klik `OK`.
* Klik `OK` pada window `Environment Variables` --> klik `OK` lagi pada window `System Properties`.

##GIT

* Untuk mengunduh Git, [klik di sini](http://git-scm.com/download/win). Tunggu sampai unduhan selesai.
* Pada file yang telah diunduh klik kanan lalu klik `Run as administrator`.
* Pada window `User Account Control` klik `Yes`.
* Pada window `Git Setup` klik `Next >` --> `Next >` --> `Next >` --> pilih `Use Git from the Windows Command Prompt` --> `Next >` --> `Next >` --> tunggu sampai proses instalasi selesai.
* Buka `Command Prompt` dan ketik `git` untuk memeriksa apakan Git sudah berhasil terinstal atau belum.

##MERCURIAL (Hg)

* Untuk mengunduh Hg, [klik di sini](http://mercurial.selenic.com/wiki/Download). Pilih `Mercurial-3.3 (32-bit msi)` atau `Mercurial-3.3 (64-bit msi)` sesuai jenis PC anda. Tunggu sampai unduhan selesai.
* Ikuti proses instalasi sampai selesai dengan meng-klik `Next >`.
* Buka `Command Prompt` dan ketik `hg` untuk memeriksa apakan Mercurial sudah berhasil terinstal atau belum.

###Pengaturan Properties:

* Buka `File Explorer` --> klik kanan `Computer` atau `MyComputer` atau `This PC` (sesuai nama yang diberikan pada masing-masing komputer) --> klik `Properties` --> klik `Advanced system settings`
* Pada window `System Properties` pilih pengaturan `Advanced` --> klik `Environment Variables...`
* Pada window `Environment Variables` klik `New...` pada bagian `User variables for [nama komputer]`
* Pada window `New User Variable` edit `PATH` dengan menambahkan Variable value nya menjadi `%GOPATH%\bin;%GOROOT%\bin;C:\Program Files\Mercurial` --> klik `OK`
* Klik `OK` pada window `Environment Variables` --> klik `OK` lagi pada window `System Properties`.

##GORILLA



