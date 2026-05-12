# marketoblik - Система обліку замовлень для мережі магазинів

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/marketoblik-configs)](https://github.com/YOUR_USERNAME/marketoblik-configs)

**marketoblik** — це веб-додаток для управління замовленнями в мережі магазинів. Система дозволяє:

- Оформлювати замовлення товарів
- Відстежувати історію замовлень
- Синхронізувати дані між магазинами однієї локації
- Адмініструвати акції та статуси товарів
- Отримувати сповіщення про нові накладні в Telegram

## Швидкий старт

### Для користувача
1. Перейдіть за посиланням: **[MarketOblik Sklad](https://marketoblik.web.app/sklad/)**
2. Введіть номер свого магазину (наприклад, `11`, `25`, `27`, `29`, `333`)
3. Почніть замовляти товари!

### Для адміністратора
Детальна інструкція: [ADMIN_GUIDE.md](./docs/ADMIN_GUIDE.md)

## 📁 Структура репозиторію

| Файл | Призначення |
|------|-------------|
| `assets/storage/marketoblik_versions.txt` | Версії та контроль системних вкладок |
| `assets/storage/marketoblik_parametrs.txt` | Магазини, локації, контакти |
| `assets/storage/marketoblik_codes.txt` | База кодів та категорій |
| `assets/storage/marketoblik_*.txt` | Контент відділів (хліб, випічка, суші тощо) |

## 🛠 Технології

- **Frontend**: Vanilla JS, HTML5, CSS3
- **Backend**: Firebase (Realtime Database), Azure
- **Cloud Functions**: Google Cloud Functions
- **Хостинг**: Firebase Hosting + GitHub Raw

## 📞 Контакти

- GitHub Issues: [Створити звіт](https://github.com/onuspell/marketoblik-configs/issues)
- Email: andriievoleh050@gmail.com

## 📄 Ліцензія

MIT License - вільне використання та модифікація
