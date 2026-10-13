# Tugas6_SistemOperasi

1.Eksekusi seluruh profile yang ada

a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut:

<img width="1280" height="429" alt="satu a5" src="https://github.com/user-attachments/assets/2fa71bc8-a857-4cb2-b9aa-a65bdc259126" />

b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu:

<img width="1280" height="800" alt="1b foto pertama" src="https://github.com/user-attachments/assets/1e14da86-305e-4d09-a0c8-ecd58da5b245" />

<img width="1280" height="800" alt="1b foto 3" src="https://github.com/user-attachments/assets/bc1609a9-8fef-44cc-ae2d-635a3cb17805" />


c. Jalankan instruksi substitute user, kemudian keluar dengan perintah exit sebagai berikut:

<img width="1280" height="419" alt="1c tugas 5" src="https://github.com/user-attachments/assets/61711f7a-7c8b-42c0-b64d-0501e65fc8d6" />

Perbedaan kedua utilitas tersebut adalah:

su username : beralih ke pengguna lain tanpa melalui lingkungan login secarah penuh.

su - username : Beralih ke pengguna lain dengan lingkungan login, termasuk pengaturan lingkungan dan pembacaan file profile login yang sesuai.

2. Prompt String (PS)
   
a. Edit file .bash_profile, ganti prompt PS1 dengan parameter nama variabel tersebut, agar berlaku oleh semua shell.

<img width="1280" height="270" alt="2b pratikum5" src="https://github.com/user-attachments/assets/2db749f8-7003-4384-b2e4-6774b50d44b3" />

b. Eksperimen hasil PS1 :

<img width="1280" height="403" alt="2b pratikum5" src="https://github.com/user-attachments/assets/a73eceea-5041-4093-8969-cc1db016c4af" />

3.Logout
Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout.

<img width="1280" height="327" alt="VirtualBox_ubuntu2604_13_10_2026_10_44_19" src="https://github.com/user-attachments/assets/f4d08534-174e-464c-99ee-94a560edcdc3" />

<img width="1280" height="197" alt="VirtualBox_ubuntu2604_13_10_2026_10_37_21" src="https://github.com/user-attachments/assets/a2b05cc3-bbe5-430a-82ce-baead8a4b1c4" />

4. Bash Script
   
a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing:

<img width="1280" height="154" alt="4a p1" src="https://github.com/user-attachments/assets/5e0ba0f3-75f8-4247-9999-b1b0c84861d4" />

<img width="1280" height="156" alt="4a p2" src="https://github.com/user-attachments/assets/8ce5ca57-1e84-459f-a4b3-716ef1e28789" />

<img width="1280" height="149" alt="4a p3" src="https://github.com/user-attachments/assets/0d13668b-a8b0-4a06-8d5e-e44273bb4aaf" />

<img width="1280" height="644" alt="4b foto pertama" src="https://github.com/user-attachments/assets/4357d0b8-ac29-4c82-a943-ca9eef07ad9f" />

b. Jalankan script tersebut sebagai berikut :

<img width="1280" height="800" alt="4b foto kedua" src="https://github.com/user-attachments/assets/cbf334fd-d4c0-448d-8be4-560f3c446e07" />

<img width="1280" height="629" alt="4b foto ketiga" src="https://github.com/user-attachments/assets/f301f746-4e01-44ce-8f7e-84ca547d136b" />

<img width="1280" height="800" alt="4b foto keempat" src="https://github.com/user-attachments/assets/f6011066-91d5-4bed-a23e-65c32e16305b" />

5. Jobs
   
a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik,
kemudian menyimpan tanggal dan jam pada file hasil.

<img width="1280" height="110" alt="5b pratikum 5" src="https://github.com/user-attachments/assets/692ccc1d-c869-4fbf-8b7b-fe0d2755c87a" />

b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di
background sebagai berikut :

<img width="1280" height="92" alt="5b yang benar pratikum5" src="https://github.com/user-attachments/assets/b1de382c-284c-4b7e-afa6-6539519ffe82" />

c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program
tersebut ke background

<img width="1280" height="147" alt="5d benarrrr c" src="https://github.com/user-attachments/assets/569c8089-6e2c-4871-a635-50c617248e20" />

d. Stop program background dengan utilitas kill

<img width="1280" height="436" alt="5d benarrrrdd " src="https://github.com/user-attachments/assets/2a699485-a172-4469-a3a6-6912303d3960" />

<img width="1179" height="85" alt="5d benarrrr terakhir" src="https://github.com/user-attachments/assets/0600b287-b332-4c7c-b56a-bec11b38c5c8" />

6. History

a. Ganti nilai HISTSIZE dari 1000 menjadi 20

<img width="1280" height="232" alt="benar 6a" src="https://github.com/user-attachments/assets/1df519ad-7dfa-4a01-aec0-f5c8b229d20b" />

b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang
terakhir dilakukan

<img width="1280" height="496" alt="6b yang benar" src="https://github.com/user-attachments/assets/82e4e48e-1136-4a9a-be26-aab9ea440790" />

c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada
history bufer

<img width="1280" height="147" alt="6c bener" src="https://github.com/user-attachments/assets/632a47fb-9815-44ab-a865-14218f300559" />

d. Ulangi instruksi pada history bufer nomor 150

<img width="1280" height="509" alt="6d yang benar nian" src="https://github.com/user-attachments/assets/ea746075-2336-4c88-9ff0-2aa0ee484845" />

e. Ulangi instruksi dengan prefix “ls”

<img width="1280" height="536" alt="6e selesai" src="https://github.com/user-attachments/assets/b778de97-c349-43b4-a51c-13c326c9e44c" />
