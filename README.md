  <img src="https://img.shields.io/static/v1?label=ViewTechTeam&color=green&message=+&logo=nano&logoColor=white&style=for-the-badge">
  <img src="https://img.shields.io/static/v1?label=Author&color=green&message=viewTech+ORG&logo=nim&logoColor=white&style=for-the-badge"><br>
  <img src="https://img.shields.io/github/stars/ViewTechOrg/Trust-YourCam?logo=github&style=for-the-badge">
  <img src="https://img.shields.io/static/v1?label=Version&color=green&message=0.0.3&logo=Clockify&logoColor=white&style=for-the-badge"><br><br>
  <img src="https://img.shields.io/github/contributors/ViewTechOrg/Trust-YourCam?logo=apache&style=for-the-badge"><br>
  <img src="https://img.shields.io/static/v1?label=Termux&color=green&message=+&logo=Iterm2&logoColor=white&style=flat">
  <img src="https://img.shields.io/github/forks/ViewTechOrg/Trust-YourCam?logo=github&style=flat"><br>
<br><br>
# DEFACE_JSO

**DEFACE_JSO** adalah script berbasis bash untuk membantu dalam pembuatan script deface otomatis menggunakan format JSO (JavaScript Object). Dilengkapi dengan berbagai mode spam dan fleksibilitas dalam pemanggilan script.

## Apa Itu Deface?

**Deface** adalah tindakan menyisipkan atau mengubah konten pada halaman website, biasanya dilakukan dengan cara mengeksploitasi celah keamanan. Tujuannya bisa bermacam-macam, mulai dari sekadar iseng, menyampaikan pesan tertentu, hingga menunjukkan kerentanan sistem.

Dalam konteks script ini, deface dilakukan dengan cara membuat dan mengirimkan file **.jso (JavaScript Object)** yang berisi tampilan halaman palsu atau hasil modifikasi, sehingga tampilan website target berubah dari aslinya.

**PENTING:** Script ini hanya untuk edukasi dan pengujian sistem milik sendiri. Jangan gunakan tanpa izin!

## Fitur

- **JSO Generate**  
  Membuat file deface dengan format `.jso` secara otomatis.

- **Mode Spam Berturut-turut**  
  Mengirimkan file deface ke target secara terus-menerus tanpa henti.

- **Mode Spam Satu Putaran**  
  Mengirimkan file deface satu kali ke semua target yang tersedia.

- **Login Script Universal**  
  Script login dapat dipanggil dari direktori mana pun di sistem.

## Instalasi

Pastikan kamu menggunakan Termux atau terminal Linux yang mendukung `bash`.

```bash
pkg update
pkg upgrade
pkg install git curl -y
cd $HOME
git clone https://github.com/ViewTechOrg/DEFACE_JSO
cd DEFACE_JSO
bash deface.sh
