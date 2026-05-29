<p align="center"><img width="83" height="41" alt="logo" src="https://github.com/user-attachments/assets/3ae1d157-bf95-4471-bc2f-50c2f56d2a66" />
</p>


<h1 align="center">
🏷️ Label Generator App
</h1>

<p align="center">
<strong>A clean, fully local label generator for warehouses, packaging teams, sellers, and marketplace workflows.</strong>
</p>

<p align="center">
No installation • Offline • Browser-based • Print-ready
</p>

<p align="center">
  <a href="../../releases">📦 Download</a> •
  <a href="#overview">📖 Overview</a> •
  <a href="#key-features">✨ Features</a> •
  <a href="#presets">🏪 Presets</a> •
  <a href="#how-to-use">🚀 Quick Start</a> •
  <a href="#license">📄 License</a>
</p>

Русская версия находится ниже: [перейти к описанию на русском](#генератор-этикеток).


<img width="1200" height="728" alt="Twitter post - 1" src="https://github.com/user-attachments/assets/918d35a3-2a85-4122-9541-dc07d985011f" />
<img width="1200" height="653" alt="Twitter post - 2" src="https://github.com/user-attachments/assets/d69f1bf2-75f3-44e4-8a27-f20557e30bb6" />

---

# Overview

**Label Generator App** helps create print-ready product labels directly in the browser. The application is built as a standalone HTML file, so it does not require a server, database, registration, cloud storage, or external services.

The current version has been redesigned to feel more practical and pleasant in daily work: the settings are grouped more clearly, the preview is easier to read, marketplace presets are faster to switch, and the printed label layout is aligned with the on-screen preview.

---

## Key Features

| Feature | Description |
|----------|-------------|
| ✅ Fully local and offline-ready | Open the HTML file in a browser and work without installation |
| ⚡ Live label preview | Every field update is reflected immediately |
| 🖨️ Print-ready layout | Print directly or save as PDF through the browser |
| 🎨 Updated visual interface | Cleaner spacing, clearer controls, smoother workflow |
| 🌍 Bilingual UI | English and Russian interface modes |
| 📏 Flexible label size | Custom dimensions in `px`, `cm`, or `mm` |
| 🏪 Marketplace presets | Ready-made layouts for selling and warehouse scenarios |
| 📦 Barcode generation | Product and marketplace barcodes rendered inside labels |
| 🔳 Data Matrix support | Generates marking code from Data Matrix field |
| 🛡️ Honest Sign support | Data Matrix placed above number/SKU where relevant |
| 📝 Marketplace-specific fields | SKU, quantity, expiration, size, serial number, comments |
| 🚀 No dependencies | Pure HTML, CSS, and JavaScript |

---

## Presets

### 🏷️ Custom Label

Use this mode for general product labels, internal warehouse labels, samples, packaging labels, and non-marketplace scenarios. You can set a custom size and choose the barcode type manually.

---

### 🟦 OZON

Marketplace-oriented label layout with fields for product name, seller article, Ozon SKU ID, quantity, expiration date, color, size, storage conditions, barcode, number/SKU, and optional Data Matrix marking.

**Default size:** `120 x 75 mm`

---

### 🟪 Wildberries

Compact marketplace label layout with product name, seller article, WB NM ID, brand, country of origin, supplier, quantity, expiration date, color, size, barcode, number/SKU, and optional Honest Sign/Data Matrix code.

**Default size:** `58 x 40 mm`

> [!IMPORTANT]
> The print layout for this preset has been fixed so the printed version matches the preview more closely.

---

### 🟥 Yandex Market

Dedicated Yandex Market preset with a marketplace-specific layout. It supports product name, description, composition, shelf life text, serial number, seller article, quantity, expiration date, color, size, barcode, SKU, and optional Data Matrix marking.

**Default size:** `100 x 70 mm`

---

### 📦 Universal FBS Label

A flexible FBS label for shipments where the seller prepares the package before transfer to a marketplace or logistics partner. It includes marketplace name, order number barcode, shipment number, seller article, quantity, warehouse comment, product barcode, SKU, and optional Data Matrix marking.

**Default size:** `100 x 70 mm`

---

## Supported Data

The application can display and print:

- Product name
- Packaging date
- Weight and weight unit
- Barcode value
- Number / SKU
- Seller article
- Quantity
- Expiration date
- Product color and size
- Storage conditions
- Marketplace SKU or identifier
- Brand, country of origin, and supplier
- Product description and composition
- Shelf life text
- Serial number
- Order and shipment numbers
- Warehouse comment
- Data Matrix marking code

---

## Barcode And Marking

The app supports common product and marketplace barcode scenarios, including numeric EAN barcodes and Code128 for marketplace/order identifiers.

### Supported Barcode Types

- EAN-8
- EAN-13
- EAN-14
- EAN-18
- Code128
- Data Matrix

For marked goods, the **Data Matrix marking code** can be entered into the dedicated field. The app generates the visual Data Matrix code and places it into the label layout without requiring an external service.

---

## How To Use

1. Open the HTML file in a modern browser.
2. Select a preset or use the custom label mode.
3. Fill in the product, barcode, SKU, and marketplace fields.
4. Check the live preview.
5. Click **Open preview / Print**.
6. Print the label or save it as PDF from the browser dialog.

### Recommended browsers

- Microsoft Edge
- Google Chrome
- Mozilla Firefox
- Safari

---

## Current Main File

The latest expanded working version is:

```txt
index.html
```

It includes the optimized codebase, updated visual interface, Wildberries print fix, Honest Sign/Data Matrix generation, Yandex Market preset, and Universal FBS preset.

---

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- SVG rendering for barcodes
- Canvas/SVG-style rendering for Data Matrix

> [!NOTE]
> No frameworks. No backend. No tracking. No database.

---

## Notes

Marketplace and marking requirements can change, so label layouts should be checked against the current rules of the platform before mass printing.

---

## License

Free to use for personal and commercial purposes.
Developed by @nimisss556 (https://t.me/nimisss556)
Copyright © 2026 dreambulka.
Original project: https://github.com/dreambulka/Label-Generator-App

---

# Генератор этикеток

Удобный локальный генератор этикеток для складов, упаковки, продавцов и работы с маркетплейсами.

English version is above: [go to English description](#label-generator-app).

---

## Описание

**Label Generator App** помогает быстро создавать готовые к печати товарные этикетки прямо в браузере. Приложение сделано как автономный HTML-файл, поэтому ему не нужны сервер, база данных, регистрация, облако или внешние подключения.

В текущей версии обновлён визуал: интерфейс стал чище, современнее и удобнее для ежедневной работы. Настройки лучше сгруппированы, предпросмотр читается спокойнее, пресеты маркетплейсов переключаются быстрее, а печатная версия этикетки лучше соответствует тому, что видно в предпросмотре.

---

## Возможности

| Возможность | Описание |
|-------------|----------|
| ✅ Полностью локальная работа | Можно открыть HTML-файл в браузере и пользоваться без установки |
| 🌐 Работа офлайн | Данные не отправляются на сервер |
| ⚡ Живой предпросмотр | Изменения сразу отображаются |
| 🖨️ Печать и PDF | Через стандартное окно браузера |
| 🎨 Обновлённый интерфейс | Аккуратнее, удобнее и современнее |
| 🌍 Два языка | Русский и английский |
| 📏 Размеры | `px`, `cm`, `mm` |
| 🏪 Пресеты маркетплейсов | Ozon, WB, Яндекс, FBS |
| 📦 Штрихкоды | Генерация прямо внутри этикетки |
| 🔳 Data Matrix | Генерация маркировки |
| 🛡️ Честный ЗНАК | Автоматическое размещение |
| 🚀 Без зависимостей | Только HTML, CSS, JavaScript |

---

## Пресеты

### Произвольная этикетка

Подходит для обычных товарных этикеток, внутренней складской маркировки, упаковки, образцов и нестандартных задач. Можно задать свой размер этикетки и вручную выбрать тип штрихкода.

### OZON

Макет для задач Ozon: название товара, артикул продавца, Ozon SKU ID, количество, срок годности, цвет, размер, условия хранения, штрихкод, номер/SKU и опциональный Data Matrix.

**Размер по умолчанию:** `120 x 75 мм`

### Wildberries

Компактный макет для Wildberries: название товара, артикул продавца, WB NM ID, бренд, страна производства, поставщик, количество, срок годности, цвет, размер, штрихкод, номер/SKU и опциональный Честный ЗНАК/Data Matrix.

**Размер по умолчанию:** `58 x 40 мм`

> [!IMPORTANT]
> Для этого пресета исправлена печатная версия: теперь она лучше совпадает с предпросмотром.

### Яндекс Маркет

Отдельный пресет для Яндекс Маркета с собственным макетом. Поддерживает название товара, описание, состав, срок службы/годности, серийный номер, артикул продавца, количество, срок годности, цвет, размер, штрихкод, SKU и опциональный Data Matrix.

**Размер по умолчанию:** `100 x 70 мм`

### Универсальная FBS-этикетка

Гибкий макет для FBS-сценариев, когда продавец сам готовит заказ к передаче маркетплейсу или логистическому партнёру. В этикетке есть название маркетплейса, штрихкод заказа, номер отправления, артикул продавца, количество, комментарий для склада, товарный штрихкод, SKU и опциональный Data Matrix.

**Размер по умолчанию:** `100 x 70 мм`

---

## Какие данные можно вывести

Приложение поддерживает вывод:

- Названия товара
- Даты упаковки
- Веса и единицы измерения
- Значения штрихкода
- Номера / SKU
- Артикула продавца
- Количества
- Срока годности
- Цвета и размера товара
- Условий хранения
- SKU или идентификатора маркетплейса
- Бренда, страны производства и поставщика
- Описания и состава товара
- Текста срока службы/годности
- Серийного номера
- Номера заказа и отправления
- Комментария для склада
- Кода маркировки Data Matrix

---

## Штрихкоды и маркировка

Приложение поддерживает распространённые сценарии товарных и маркетплейс-штрихкодов, включая числовые EAN-форматы и Code128 для заказов, SKU и внутренних идентификаторов.

### Поддерживаемые типы штрихкодов

- EAN-8
- EAN-13
- EAN-14
- EAN-18
- Code128
- Data Matrix

Для маркированных товаров можно заполнить поле **Data Matrix marking code**. Приложение сформирует визуальный Data Matrix и разместит его в макете этикетки без обращения к внешним сервисам.

---

## Как пользоваться

1. Откройте HTML-файл в современном браузере.
2. Выберите нужный пресет или произвольную этикетку.
3. Заполните данные товара, штрихкод, SKU и поля маркетплейса.
4. Проверьте живой предпросмотр.
5. Нажмите **Open preview / Print**.
6. Распечатайте этикетку или сохраните её в PDF через окно печати браузера.

### Рекомендуемые браузеры

- Microsoft Edge
- Google Chrome
- Mozilla Firefox
- Safari

---

## Текущий основной файл

Актуальная расширенная версия:

```txt
index.html
```

В ней уже есть оптимизированный код, обновлённый визуал, исправление печати для Wildberries, генерация Честного ЗНАКа/Data Matrix, пресет Яндекс Маркета и универсальный FBS-пресет.

---

## Технологии

- HTML5
- CSS3
- Чистый JavaScript
- SVG-генерация штрихкодов
- Генерация Data Matrix внутри приложения

> [!NOTE]
> Без фреймворков. Без бэкенда. Без отслеживания. Без базы данных.

---

## Важно

Требования маркетплейсов и правила маркировки могут меняться, поэтому перед массовой печатью этикетки стоит сверять с актуальными правилами конкретной площадки.

---

## Лицензия

Бесплатно для личного и коммерческого использования.
Developed by @nimisss556 (https://t.me/nimisss556)
Copyright © 2026 dreambulka.
Original project: https://github.com/dreambulka/Label-Generator-App
