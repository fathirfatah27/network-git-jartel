Nama : Muhammad Fathir Fatah
Nim   : 607052430002
Kelas : 48-02
Ujikom 1 Jaringan Telekomunikasi

Soal 1: Konfigurasi Server VoIP (Asterisk on Ubuntu)
1.	Konfigurasi Asterisk pada Ubuntu.
Login 
user :vboxuser
Pw  : changeme

Buat configurasi sudo nano /etc/asterisk//sip.conf
Isi dengan 
[1001]
type=friend
username=002
secret=1234
context=internal
callerid=”Fathir” <002>

[1002]
type=friend
username=003
secret=1234
context=internal
callerid=”Fatah” <003>



3. Masuk ke Asterisk CLI
sudo asterisk -rvvv

4. Cek User SIP
sip show peers

5. Konfigurasi Zoiper
User:1001 dan  1002
Pw:1234
10.191.113.210
 
 

