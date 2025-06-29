IyoNie v2.0 Live adalah asisten AI secara langsung berkomunikasi dengan alat untuk menjawab pertanyaan dari pengguna dengan tekan tombol touch pengguna akan mendapat jawaban dari IyoNie tentang humidity dan temperature (AI Thingking), pengguna juga dapat memasukan pertanyaan pada halaman kontrol.

# Demo Video
- [Video 1](https://www.instagram.com/suryodwijayanto/reel/DLSWLqYPcs6/)
- [Video 2](https://www.instagram.com/suryodwijayanto/reel/DLW4CGkPT7I/)

# Instalasi Papan
[<img alt="LuckNet Reference Board Manage" title="LuckNet Reference Board Manage" width="50%" src="https://raw.githubusercontent.com/CusMeDroid/IyoNie/refs/heads/main/IyoNie-v2-0.png" />](https://raw.githubusercontent.com/CusMeDroid/IyoNie/refs/heads/main/IyoNie-v2-0.png)

# Item
1. Wemos D1 Mini ESP8266
2. Mini Oled 128x64
3. DHT11
4. Touch

# Logika
```txt
   ______ IyoNie Setup
  |      |
  |      |______ Portal
  |             |
  |             |______ Hotspot/WiFi (STA)
  |             |
  |             |______ API
  |             |
  |             |______ Set WiFi (AP)
  |             |
  |_____________|____________ Enjoy
```

# IyoNie Sistem
if (Halaman Portal) {
>Berfungsi untuk mengatur setup awal, Jika semua terkoneksi dengan benar maka akan masuk ke Halaman kontrol

} else if (Halaman Kontrol) {
>Adalah pengaturan pendukung, terdapat inputan untuk membuat pertanyaan, gulir/scroll up/down, Bersihkan & Ulangi dan Factory Reset/Kembali ke setelan awal

}

# Instalasi firmware
[Klik Saya](mailto:iyortml@gmail.com)

# Rilis
2025 - SURYO DWIJAYANTO
