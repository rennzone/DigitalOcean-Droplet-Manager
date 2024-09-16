<h1>DigitalOcean Droplet Manager</h1>

![Screenshot_1](https://github.com/user-attachments/assets/8ed87dcc-8367-4617-86bf-e9508ddcbf8e)


Manajemen Droplet DigitalOcean dengan menggunakan API Key. Kalian bisa melakukan deploy, destroy, restart dan rebuild Droplet secara cepat tanpa harus login via Web.
Dibuat dengan menggunakan bash, curl dan segelas kopi panas ☕

## **Fitur**



- **Droplet List**
<br>Memberikan informasi tentang droplet yang dimiliki oleh user beserta IP, OS, Size dan tanggal dibuatnya.
- **Deploy**
<br>Memberikan perintah untuk membuat droplet sesuai dengan spesifikasi yang diminta.
- **Destroy**
<br>Memberikan perintah untuk menghapus droplet yang ada.
- **Reboot**
<br>Memberikan perintah untuk melakukan reboot pada droplet yang ada.
- **Rebuild**
<br>Memberikan perintah untuk menginstall ulang OS pada droplet yang ditentukan.

## **Cara Penggunaan**



1. Download Script

```bash
wget https://raw.githubusercontent.com/rennzone/DigitalOcean-Droplet-Manager/main/do-manager.sh
```

2. Jalankan Script

```bash
bash do-manager.sh
```

3. Input API Key

Pastekan API Key kalian

4. Input Fitur yang ingin dijalankan

Pilih opsi 1-4, kemudian enter. Pilih '0' untuk exit.

## Note



- API Key harus memiliki full access.
- Beberapa OS tidak bisa digunakan pada saat rebuild. Saya akan update nanti.
