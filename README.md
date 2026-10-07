# 🔌 Arduino → Python Serial Bridge

![Arduino](https://img.shields.io/badge/Arduino-informational?style=flat-square) ![Python](https://img.shields.io/badge/Python-informational?style=flat-square) ![pySerial](https://img.shields.io/badge/pySerial-informational?style=flat-square)

**<img src="https://raw.githubusercontent.com/canayglr/canayglr/main/assets/flags/gb.png" height="14" alt="EN"/>** The Arduino sketch sends sensor readings over the serial port; the Python script reads them with **pySerial**, validates them as integers and prints them. A minimal base for hardware ↔ PC data pipelines.

**<img src="https://raw.githubusercontent.com/canayglr/canayglr/main/assets/flags/tr.png" height="14" alt="TR"/>** Arduino kodu sensör verilerini seri porttan gönderir, Python scripti **pySerial** ile okur, tam sayıya çevirerek doğrular ve ekrana yazar. Donanım ile bilgisayar arasında veri aktarımı için temel bir yapı.

## Run / Çalıştırma
```bash
pip install pyserial
python index.py   # change COM6 to your port / portu kendinize göre değiştirin
```
