# 🔌 Arduino → Python Serial Bridge

![Arduino](https://img.shields.io/badge/Arduino-informational?style=flat-square) ![Python](https://img.shields.io/badge/Python-informational?style=flat-square) ![pySerial](https://img.shields.io/badge/pySerial-informational?style=flat-square)

**🇬🇧** The Arduino sketch sends sensor readings over the serial port; the Python script reads them with **pySerial**, validates them as integers and prints them. A minimal base for hardware ↔ PC data pipelines.

**🇹🇷** Arduino kodu sensör verilerini seri porttan gönderir, Python scripti **pySerial** ile okur, tam sayıya çevirerek doğrular ve ekrana yazar. Donanım ile bilgisayar arasında veri aktarımı için temel bir yapı.

## Run / Çalıştırma
```bash
pip install pyserial
python index.py   # change COM6 to your port / portu kendinize göre değiştirin
```
