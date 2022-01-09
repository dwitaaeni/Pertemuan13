# pertemuan13
## Profil
- Nama : D.Wita Aeni
- Nim : 312110222
- Kelas : TI.21.A.1

## TUGAS PERTEMUAN 13
- Implementasikan penggunaan eksepsi pada lab-lab
sebelumnya untuk mengatasi error yang ditimbulkan.<P>

- Saya menggunakan eksepsi pada tugas sebelum nya di bagian input data.
Berikut adalah tambahan kode eksepsi.<P>

    while True:
            try:
                nim = int(input("Masukan NIM\t: "))
                if nim == "":
                    print("NIM tidak boleh kosong")
                else:
                    break
            except:
                print("Harap Masukan Angka")
            else:
                break
            
    while True:
            try:
                nilai = int(input("Masukan Nilai\t: "))
                if nilai == "":
                    print("Nilai tidak boleh kosong")
                else:
                    break
            except:
                print("Harap Masukan Angka")
            else:
                break

- Dengan menambahakan eksepsi maka:<P>
    - Saat input data kosong maka akan meminta untuk memasukan data kembali<P>
    - Saat input NIM dan Nilai menggunakan karakter maka program akan meminta untuk memasukan angka.<P>
![gambar 1](Screenshot/Screenshot1.png)