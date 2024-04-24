### Описание бота для Telegram
Писать в ТГ  [pay4fall](https://t.me/pay4fallwall)

**Стоимость:** 20,000₽ / USDT По курсу

#### Стэк технологий:
- PostgreSQL
- Redis
- Nginx
- Docker
- Python
- aiogram3
- FastAPI

#### Основной функционал:

1. **Реферальная система:** 
   - Настройка количества дней доступа для пригласившего и приглашенного после оплаты рефералом.

2. **Платежные системы:** 
   - **ЮКасса:** Прямо в Телеграм
   - **Aaio, LAVA:** Ссылка или Telegram WebApp

3. **Личный кабинет пользователя:** 
   - Информация о текущих доступах, срок, стоимость, локация.
   - Меню с ключами.
   - Изменение локации доступа.
   - Выбор префиксов маскировки подключения.

4. **Панель администратора:** 
   - Добавление/удаление серверов.
   - Замена сервера через админ-панель.
   - Управление тарифами, лимитами, рассылка сообщений, статистика.
   - Добавление серверов в одной стране с минимальным количеством выданных ключей.

5. **Отдельные сервисы:** 
   - Проверка и оповещение о сроках подписки.
   - Оповещение об исчерпании лимита ключей.
   - Генерация динамических ключей, маскировка подключения, настройка Nginx и SSL сертификатов.
   - Доступ к БД через SSH Port Forwarding.

#### Дополнительная информация:

- **GitHub и Docker** используются для запуска и обновлений.
- Помощь в настройке сервера, домена, бота, договора ЮКассы, настройка Aaio. Ключи LAVA предоставляются менеджером.
- Планируемые доработки и исправления/улучшения существующего функционала предоставляются бесплатно.
- Обновления из приватного репозитория GitHub.
- [Пример работающего бота](https://t.me/test_custom_vpn_bot).
- Для доступа к функционалу администрации сообщите свой Telegram ID узнав через [@getmyid_bot](https://t.me/getmyid_bot).

#### Тестовые платежные данные:
- Карта: 1111 1111 1111 1026
- Дата: 12/22
- CVV: 000

**Примечание:** Тестовый бот может лагать из-за одновременного запуска нескольких проектов на сервере.
****