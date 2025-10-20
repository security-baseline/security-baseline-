# Személyes Wi-Fi / OPSEC baseline (v1)
Dátum: 2025-__-__  |  Szerző: security-baseline

## Router
- Firmware friss? (I/N + verzió)
- Admin jelszó: min. 16+ karakter, jelszókezelőben
- Távoli admin (WAN): KI
- WPS: KI, UPnP: KI

## Wi-Fi
- SSID: nem személyes név
- Titkosítás: WPA3 (vagy WPA2-AES), **TKIP tilos**
- Jelszó: 14–16+ véletlen karakter
- Vendégháló külön SSID/jelszó, LAN-hozzáférés tiltva

## Szeparáció
- IoT külön hálón (guest/VLAN), IoT→LAN tilt, IoT→Internet enged

## Naplózás
- Config backup letöltve és titkosítva tárolva (hely: …)
- Változásnapló: dátum + mi módosult

## Gyors ellenőrzőlista
- [ ] Firmware friss • [ ] WPS/UPnP KI • [ ] WPA3/WPA2-AES
- [ ] Vendégháló szeparált • [ ] Erős admin+Wi-Fi jelszó • [ ] Backup megvan
