# simpledesk-build-deps

Kopien von Dateien, die der SimpleDesk-Build herunterlädt. Früher kamen sie direkt von RustDesk.
Jede Datei liegt als Release-Anhang hier. Der Build prüft sie mit der sha256 aus dieser Tabelle.

Die Dateien sind unverändert. Sie wurden am 2026-11-13 von den angegebenen Quellen geladen.

| Release-Tag | Datei | Größe (Bytes) | sha256 | Quelle |
|---|---|---|---|---|
| `flutter-engine-windows-x64-2024-12-01` | `windows-x64-release.zip` | 63301215 | `ec8cabf36ee4ff24c8d98de25b00e70781eb03876265aee84d0fe554a110036e` | github.com/rustdesk/engine, Release `main`, Anhang vom 2024-12-01 |
| `usbmmidd_v2` | `usbmmidd_v2.zip` | 199309 | `629b51e9944762bae73948171c65d09a79595cf4c771a82ebc003fbba5b24f51` | github.com/rustdesk-org/rdev, Release `usbmmidd_v2` |
| `printer-driver-v4-1.4` | `rustdesk_printer_driver_v4-1.4.zip` | 34789 | `c4cf4d3b48c4d9079b243edc43bb1db03b076282bc259c9f49883e9db20fa8b5` | github.com/rustdesk/hbb_common, Release `driver` |
| `printer-driver-v4-1.4` | `printer_driver_adapter.zip` | 534603 | `e90e5d52c8807b4c6293c78a52479338715e0bf396b1b34802777b8c452e6781` | github.com/rustdesk/hbb_common, Release `driver` |

Hinweise:

- Für die Engine und usbmmidd_v2 gibt die Quelle keine Prüfsumme an. Die sha256 oben ist die der geladenen Datei.
- Die Prüfsummen des Druckertreibers stimmen mit der `sha256sums` der Quelle überein.
- Lizenzen gelten wie bei der Quelle. usbmmidd_v2 ist ein Treiber von Amyuni Technologies.
