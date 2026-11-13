# SimDash: готовые версии

Дисплей телеметрии для автосимуляторов (Waveshare ESP32-S3-Touch-LCD-1.69) и программа SimDash Bridge для Windows: читает Assetto Corsa и Automobilista 2 и передаёт на дисплей по USB скорость, передачу, обороты, время круга, флаги, топливо и данные ПК.

В этом репозитории публикуются только готовые версии: `SimDashBridge_X.Y.Z.exe` (прошивка дисплея встроена в него) и `SimDash-firmware_X.Y.Z.bin`. Исходный код закрыт.

## Скачать

Последняя версия: **[Releases → Latest](https://github.com/pkvform/SimDash-releases/releases/latest)**. Скачайте `SimDashBridge_X.Y.Z.exe` из раздела Assets.

- Windows 10 или 11, 64-разрядная. Установка не нужна: положите файл в любую папку и запустите.
- Windows SmartScreen может предупредить о неизвестном издателе (exe не подписан): «Подробнее», затем «Выполнить в любом случае».
- Контрольные суммы лежат в `SHA256SUMS.txt`. Проверить в PowerShell: `Get-FileHash .\SimDashBridge_X.Y.Z.exe -Algorithm SHA256`.

## Обновление

Bridge при запуске и раз в 12 часов проверяет этот репозиторий и сообщает о новой версии (отключается в «Настройках»). Скачайте новый exe, положите рядом со старым и запустите: он сам закроет старую версию, настройки в `simdash-bridge.json` сохранятся. Затем в карточке «Прошивка» нажмите «Обновить», чтобы прошить дисплей по USB.

## Отказ от ответственности

Программа и прошивка предоставляются «как есть», без каких-либо явных или подразумеваемых гарантий. Автор и правообладатель не несут ответственности за любой ущерб, включая повреждение оборудования и потерю данных, возникший в результате использования программы, невозможности её использования или её неправильной работы. Используя программу, вы соглашаетесь с условиями в [LICENSE](LICENSE).

---

**SimDash: released builds.** Sim-racing telemetry display and the SimDash Bridge Windows app. This repository only hosts `SimDashBridge_X.Y.Z.exe` (firmware embedded) and the firmware `.bin`; the source code is private. Provided "as is", without warranty of any kind; see [LICENSE](LICENSE).

© 2026 Polianskii Konstantin
