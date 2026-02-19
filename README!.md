🚀 TP-Link WR841N v11: OpenWrt Installation Guide
[RU] Оживляем легенду: Гайд для новичков

⚠️ ВНИМАНИЕ (DISCLAIMER)

Прошивка — это «операция на мозге» устройства. Вы делаете это на свой страх и риск. Если в процессе отключится питание, роутер станет «кирпичом».

1. Подготовка

• Устройство: TP-Link TL-WR841N v11 (проверьте версию на наклейке снизу!).

• Файл: `openwrt-19.07.10-ath79-tiny-tplink_tl-wr841-v11-squashfs-factory-eu.bin`.

• Важно: Шейте ТОЛЬКО через кабель LAN. Не используйте Wi-Fi!

2. Процесс установки

1. Подключите ПК к LAN-порту роутера.

2. Откройте 192.168.0.1 (логин/пароль: `admin`).

3. Перейдите в System Tools -> Firmware Upgrade.

4. Выберите файл прошивки и нажмите Upgrade.

5. Подождите 5-10 минут до полной перезагрузки.

3. Настройка (SSH)

У OpenWrt версии Tiny нет веб-интерфейса. Доступ только через консоль. Новый IP: `192.168.1.1` Команда для Windows 11: `ssh -o HostKeyAlgorithms=+ssh-rsa root@192.168.1.1` (На вопрос введите `yes`, пароля изначально нет — жмите Enter)

---

[EN] Reviving the Legend: Beginners Guide

⚠️ WARNING (DISCLAIMER)

Flashing your router is "brain surgery" for the device. You do this at your own risk. If the power goes out, the router may become a "brick".

1. Prerequisites

• Device: TP-Link TL-WR841N v11.

• Firmware: OpenWrt 19.07.10 (Tiny) EU version.

• Connection: Ethernet cable (DO NOT flash via Wi-Fi).

2. Installation

1. Connect via LAN, open 192.168.0.1.

2. Go to System Tools -> Firmware Upgrade.

3. Upload the file and click Upgrade.

4. Wait 5-10 mins.

3. Console Access (SSH)

New IP: `192.168.1.1` Windows 11 Command: `ssh -o HostKeyAlgorithms=+ssh-rsa root@192.168.1.1` (Type `yes` when prompted, no default password)

4. Commands / Команды

• `free -m` — RAM / Память.

• `df -h` — Storage / Место.

• `passwd` — Set password / Пароль.
