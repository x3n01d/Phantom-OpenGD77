# Phantom — MD-UV380 Plus / MD-UV390 Plus / MD-UV390 10W

Custom firmware for **TYT MD-UV380 Plus**, **MD-UV390 Plus** and **MD-UV390 10W (non‑Plus)**,
built on **OpenGD77-AES256** (OpenGD77 R20260131 + DMRA AES-256).

**Phantom** keeps the full OpenGD77 feature set and adds a redesigned UI:
TA2TWC screens, dual RX, analog RSSI, a fast spectrum, TX statistics and 8‑colour level bars.

---

## Features

- **Dual RX** (two lines, A/B) with fast switching.
- **TA2TWC screens** — redesigned home screens, TX statistics (PWR / voltage / temperature).
- **Analog RSSI** — S1…S9 / +60 arc, needle, peak hold, dBm.
- **Fast spectrum** — 4 ms step, peak hold, stops and **plays audio** on a captured signal.
- **Spectrum from a channel** — long‑press `#` on a channel opens the sweep for that channel.
- **8‑colour volume/squelch bar** (cyan → green → yellow → orange → red → magenta).
- **Battery icon** next to the percentage, filled by level.
- **Languages:** English, Русский, Українська (+ 18 `.gla` language files).
- Stock theme, stock splash and stock power‑off screen are preserved.

## Build

| Item | Value |
|---|---|
| Platform | TYT **MD-UV380 Plus**, **MD-UV390 Plus**, **MD-UV390 10W (non‑Plus)** |
| Base | OpenGD77-AES256 (OpenGD77 R20260131) |
| Build flags | `ENABLE_DUAL_SCREEN=1 ENABLE_TA2TWC_SCREENS=1 ENABLE_FAST_SCAN=1` |
| Binary | `openuv380-10w.bin` — **797,420 bytes** |
| SHA‑256 (bin) | `39cf827f7a6cdac31841f22172014e5cd7a29112a7e1603a20c5ff69f7fc17f4` |
| Archive | `Phantom_MD-UV390_10W.zip` — **278,321 bytes** |
| SHA‑256 (zip) | `03a2ef328100899a4546f54eb9796a0f645defd8f1980c64210875086b626c0a` |

> The AMBE+2 codec is **not** included — merge it from an official **MD‑9600 V5** donor at flash time.

## Install

1. Back up your codeplug and calibration.
2. Flash `openuv380-10w.bin` with your OpenGD77 loader (donor required).
3. Copy the `.gla` language files as usual.

## Credits

- **OpenGD77** — Roger VK3KYY, Kai DG4KLU and contributors.
- **OpenGD77-AES256** — dondch.
- Phantom — **x3n01d** & **checkra1n**.

## Disclaimer

Unofficial, community‑made firmware. AES‑256 voice is **illegal on amateur bands**
in most countries — use it only where you are licensed. Flash at your own risk.

---

# Phantom — MD-UV380 Plus / MD-UV390 Plus / MD-UV390 10W — Українська

Кастомна прошивка для **TYT MD-UV380 Plus**, **MD-UV390 Plus** та **MD-UV390 10W (non‑Plus)**
на базі **OpenGD77-AES256** (OpenGD77 R20260131 + DMRA AES‑256).

**Можливості:**
- **Dual RX** (два рядки A/B) зі швидким перемиканням;
- **екрани TA2TWC** — новий головний екран, статистика TX (PWR / напруга / температура);
- **аналоговий RSSI** — дуга S1…S9/+60, стрілка, пік, dBm;
- **швидкий спектр** — крок 4 мс, утримання піку, **звук** на захопленому сигналі;
- **спектр із каналу** — довге натискання `#` на каналі відкриває sweep;
- **8‑кольорова шкала** гучності/шумодава;
- **іконка АКБ** біля відсотків;
- **мови:** English, Русский, Українська (+ 18 `.gla`);
- стандартна тема, заставка та екран вимкнення збережені.

**SHA‑256:** `39cf827f7a6cdac31841f22172014e5cd7a29112a7e1603a20c5ff69f7fc17f4` (bin),
`03a2ef328100899a4546f54eb9796a0f645defd8f1980c64210875086b626c0a` (zip).

**Дисклеймер:** неофіційна прошивка; AES‑256 на аматорських діапазонах заборонено —
використовуйте лише там, де маєте ліцензію. Прошивка — на ваш ризик.

---

# Phantom — MD-UV380 Plus / MD-UV390 Plus / MD-UV390 10W — Русский

Кастомная прошивка для **TYT MD-UV380 Plus**, **MD-UV390 Plus** и **MD-UV390 10W (non‑Plus)**
на базе **OpenGD77-AES256** (OpenGD77 R20260131 + DMRA AES‑256).

**Возможности:**
- **Dual RX** (две строки A/B) с быстрым переключением;
- **экраны TA2TWC** — новый главный экран, статистика TX (PWR / напряжение / температура);
- **аналоговый RSSI** — дуга S1…S9/+60, стрелка, пик, dBm;
- **быстрый спектр** — шаг 4 мс, удержание пика, **звук** на захваченном сигнале;
- **спектр с канала** — долгое нажатие `#` на канале открывает sweep;
- **8‑цветная шкала** громкости/шумодава;
- **иконка АКБ** рядом с процентами;
- **языки:** English, Русский, Українська (+ 18 `.gla`);
- стандартная тема, заставка и экран выключения сохранены.

**SHA‑256:** `39cf827f7a6cdac31841f22172014e5cd7a29112a7e1603a20c5ff69f7fc17f4` (bin),
`03a2ef328100899a4546f54eb9796a0f645defd8f1980c64210875086b626c0a` (zip).

**Дисклеймер:** неофициальная прошивка; AES‑256 на любительских диапазонах запрещён —
используйте только там, где есть лицензия. Прошивка — на ваш риск.
