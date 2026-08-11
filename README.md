# Atmos Nano — GitHub Pages

Dashboard statis untuk membaca data lima sensor MQ dari Arduino Nano melalui
Web Serial di Google Chrome. Situs tidak memerlukan Python, database, atau
server aplikasi.

## Penggunaan

1. Buka alamat GitHub Pages menggunakan Chrome desktop.
2. Sambungkan Arduino Nano melalui USB.
3. Tutup Serial Monitor dan Serial Plotter Arduino IDE.
4. Klik **Hubungkan Arduino**.
5. Pilih port Arduino, misalnya **USB-SERIAL CH340 (COM6)**.

Kecepatan serial firmware harus `115200` baud. Data PPM/PPB dihitung oleh
firmware Arduino; halaman ini menerima JSON melalui Web Serial dan menampilkan
nilai serta grafiknya.
