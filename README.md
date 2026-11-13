# Phantom Firmware (OpenGD77-AES256 fork)

Custom firmware for **TYT MD-UV390 Plus 10W** and **TYT MD-UV380 Plus 10W**.

Phantom is a modified build of [OpenGD77-AES256](https://github.com/dondch/OpenGD77-AES256)
with AES-256 encryption support, rebranding, UI color defaults and build fixes.

## Features
- Advanced AES-256 DMR encryption support
- Rebranded firmware: display name **Phantom**
- Custom authors: **x3n01d** and **checkra1n**
- Build date is generated automatically at compile time
- Default home-screen colors: **RX line red**, **TX line green**
- Clean build system: `make` wipes the `build/` directory before compiling
- Calibration menu kept intact (250 mW / 1 W / 5 W / 10 W)
- Verified hardware path: Plus 10W configuration (tested working on a non-Plus MD-UV390 10W)

## Supported radios
- TYT MD-UV390 **Plus 10W**
- TYT MD-UV380 **Plus 10W**

> The firmware uses the Plus 10W hardware code path. It has been reported to run
> correctly on a standard MD-UV390 10W unit.

## Important note about DMR / AMBE
The `.bin` produced by the compiler does **not** include the AMBE codec.
Before flashing for DMR use, merge it with the official **MD-9600 V5** donor
through the bootloader.

## Calibration
Use a dummy load and a wattmeter. Calibrate 250 mW, 1 W, 5 W and 10 W points,
then save with **SK2 + Green**.

## Credits
- OpenGD77 project and contributors
- Phantom modifications: **x3n01d**, **checkra1n**

---

# Прошивка Phantom (форк OpenGD77-AES256)

Кастомна прошивка для **TYT MD-UV390 Plus 10W** та **TYT MD-UV380 Plus 10W**.

Phantom — це модифікована збірка
з підтримкою розширеного списку ключiв AES-256, ребрендингом, кольорами інтерфейсу за замовчуванням і виправленнями збірки.

## Можливості
- Розширена підтримка AES-256 шифрування DMR
- Ребрендинг прошивки: відображувана назва **Phantom**
- Автори: **x3n01d** та **checkra1n**
- Дата збірки генерується автоматично під час компіляції
- Кольори головного екрана за замовчуванням: **рядок RX — червоний**, **рядок TX — зелений**
- Чиста система збірки: `make` видаляє каталог `build/` перед компіляцією
- Меню калібрування збережено (250 мВт / 1 Вт / 5 Вт / 10 Вт)
- Перевірений апаратний шлях: конфігурація Plus 10W (працює на звичайному MD-UV390 10W)

## Підтримувані рації
- TYT MD-UV390 **Plus 10W**
- TYT MD-UV380 **Plus 10W**

> Прошивка використовує апаратний кодовий шлях Plus 10W. Повідомлялося, що вона
> коректно працює на стандартному MD-UV390 10W.

## Важливо про DMR / AMBE
`.bin`, створений компілятором, **не** містить кодек AMBE.
Перед прошиванням для DMR об'єднайте його з офіційним донором **MD-9600 V5**
через завантажувач.

## Калібрування
Використовуйте еквівалент навантаження та ватметр. Калібруйте точки
250 мВт, 1 Вт, 5 Вт і 10 Вт, потім зберігайте комбінацією **SK2 + Green**.

## Подяки
- Проєкт OpenGD77 та контриб'ютори
- Модифікації Phantom: **x3n01d**, **checkra1n**

---

# Прошивка Phantom (форк OpenGD77-AES256)

Кастомная прошивка для **TYT MD-UV390 Plus 10W** и **TYT MD-UV380 Plus 10W**.

Phantom — модифицированная сборка
с поддержкой расширеных ключей AES-256, ребрендингом, цветами интерфейса по умолчанию и исправлениями сборки.

## Возможности
- Расширеная поддержка AES-256 шифрования DMR
- Ребрендинг прошивки: отображаемое имя **Phantom**
- Авторы: **x3n01d** и **checkra1n**
- Дата сборки генерируется автоматически при компиляции
- Цвета главного экрана по умолчанию: **строка RX — красная**, **строка TX — зелёная**
- Чистая система сборки: `make` удаляет каталог `build/` перед компиляцией
- Меню калибровки сохранено (250 мВт / 1 Вт / 5 Вт / 10 Вт)
- Проверенный аппаратный путь: конфигурация Plus 10W (работает на обычном MD-UV390 10W)

## Поддерживаемые рации
- TYT MD-UV390 **Plus 10W**
- TYT MD-UV380 **Plus 10W**

> Прошивка использует аппаратный кодовый путь Plus 10W. Сообщалось, что она
> корректно работает на стандартном MD-UV390 10W.

## Важно про DMR / AMBE
`.bin`, созданный компилятором, **не** содержит кодек AMBE.
Перед прошивкой для DMR объедините его с официальным донором **MD-9600 V5**
через загрузчик.

## Калибровка
Используйте эквивалент нагрузки и ваттметр. Калибруйте точки
250 мВт, 1 Вт, 5 Вт и 10 Вт, затем сохраняйте комбинацией **SK2 + Green**.

## Благодарности
- Проект OpenGD77 и контрибьюторы
- Модификации Phantom: **x3n01d**, **checkra1n**
