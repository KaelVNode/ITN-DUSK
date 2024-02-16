Node Running Guide Dusk ITN (Tinggal Paste Paste Doang)

1️⃣# Membuat Wallet

➖ Buat New Wallet : https://wallet.dusk.network/setup/
➖ Back Up Pharse dan Masukan Lagi (Backup)
➖ Next Next Aja dan Copy Address
➖ Claim Faucet : https://faucet.dusk.network/ (Kalo Faucet Down Coba LAgi Nanti)
➖ Buat Postingan di Twitter : Address-Kalian $DUSK #ITN
➖ Salin Link Tweet Kalian dan Paste ke Faucet
➖ Klik Send Dusk

2️⃣# Open Port 

sudo ufw allow 22
sudo ufw allow 8080/tcp
sudo ufw allow 9000/udp
sudo ufw enable

3️⃣# Install Github

curl --proto '=https' --tlsv1.2 -sSfL https://github.com/dusk-network/itn-installer/releases/download/v0.1.0/itn-installer.sh | sudo sh

4️⃣# Import Pharse Wallet

rusk-wallet restore

Paste Pharse Kalian (Pastikan Huruf Kecil Semua)

Masukan Password Bebas 2x

5️⃣# Jalankan Kode di Bawah

rusk-wallet export -d /opt/dusk/conf -n consensus.keys

Masukan Password Lagi 2x

sh /opt/dusk/bin/setup_consensus_pwd.sh

Masukan Password Lagi Samain Aja

6️⃣# Start Node

service rusk start

7️⃣# Check Log Node

grep "block accepted" /var/log/rusk.log

8️⃣ # Check Wallet

rusk-wallet

➖ Pilih Acces Your Wallet dan Enter
➖ Masukan Password (Pastikan Address Kalian Sama Dengan Yang di Website)
➖ Gunakan Arah Atas Bawa Untuk Pindah Menu dan Enter Untuk Eksekusi

# Done, Tinggal Tunggu Tanggal 20 Untuk Task Stake Soon
