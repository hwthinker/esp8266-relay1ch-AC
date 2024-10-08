# Modul ESP8266 ESP-12f Relay 1 Channel  10A AC
![](https://github.com/hwthinker/esp8266-relay1ch-AC/blob/main/picture/1.png)
## Aktivasi Relay
Relay defaultnya tidak terhubung ke GPIO. Pasang Relay ke GPIO 15 agar relay bisa dkontrol oleh pin GPIO15  yang  ada di esp8266
## Cara download
![](https://github.com/hwthinker/esp8266-relay1ch-AC/blob/main/picture/2.png)
- Lepas Semua Sambungan Power supply
- Pastikan jumper relay sudah terpasang ke GPIO15 (!Penting)
- Pasang serial USB TTL dengan ketentuan RX -> TX USB Serial ; TX -> RX USB Serial; GND -> GND USB Serial; pasang 5V -> 5V USB serial 
- pasang Jumper ke IO0 dan GND
- pasang USB serial ke komputer
- Tekan dan lepas tombo reset dengan jumper tetap terpasang ke IO0 dan GND
- Download program 
- lepas jumper
- tekan dan lepas tombol reset untuk run-program
- ulang langkah awal untuk download ulang
## Source code
source code alat ini bisa di cek di [Lihat file main.cpp di sini](https://github.com/hwthinker/esp8266-relay1ch-AC/blob/main/src/main.cpp)
