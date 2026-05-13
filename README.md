# Bitcoin Price Monitor

Бот автоматически отслеживает цену биткоина и отправляет уведомления в Telegram. Все данные сохраняются в Google Sheets.

## Как работает
- Раз в минуту получает цену с CoinGecko API
- Если цена > $70000 → Telegram: "ПРОДАВАЙ"
- Если цена ≤ $70000 → Telegram: "ПОКУПАЙ"
- Каждая проверка записывается в Google Sheets

## Технологии
- n8n (автоматизация)
- Telegram Bot API
- Google Sheets API
- CoinGecko API

## Установка
1. Импортируй `Bitcoin Price in Google Sheets & Telegram Notifications` в n8n
2. Настрой Telegram бота (токен от @BotFather)
3. Настрой Google Sheets (OAuth)
4. Нажми Publish

## Скриншоты
| Telegram | Google Sheets |
|----------|---------------|
| Сообщение "ПРОДАВАЙ" | Дата, Цена, Действие |

## Автор
[@SigmaJDad](https://github.com/SigmaJDad)
