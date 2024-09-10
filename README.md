# set ntpserver

Kurulum:
sudo apt update
sudo apt-get install ntp ntpdate


Konfiürasyon dosyası:
sudo nano /etc/ntpsec/ntp.conf

Kontrol:

Silinecek satırlar:
pool ile başlayan satırları başına # koyun veya silin.

Eklanecek satir:
server 0.tr.pool.ntp.org


NTP Servisinin açılışta otomatik başlaması için:

sudo systemctl enable ntp

servisi yeniden başlatmak için:
sudo systemctl restart ntp

