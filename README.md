# 📦 API-тестирование интернет-магазина (DemoShopping)

### ✅ [Ссылка на публичную коллекцию в Postman](https://www.postman.com/flight-cosmonaut-70887455/workspace/demoshopping/collection/31214816-036db6c5-dfb6-4424-a703-ef5f34151b18?action=share&creator=31214816)

### 🔹 Изучена документация Swagger: https://qa.demoshopping.ru/api-docs
### 🔹 Составлены ручные запросы
- Авторизация и регистрация
- Получение и обновление токенов
- Получение списка товаров
- Cоздание нового товара и добавление в магазин
- Добавление товара в корзину
- Создание заказа
- Проверка статуса оплаты
- Получение истории заказов

### 🔹 Реализована цепочка запросов: от добавления товара в корзину до оплаты

### 🔹 Автоматические проверки (Postman Tests)

- Проверка статус-кодов: `200`, `400`, `401`, `404`
- Проверка тела ответа (`response body`)
- Проверка структуры JSON (ключи, значения)
- Генерация случайных данных для регистрации пользователя


# 🌍 SOAP API — Тестирование сервиса CountryInfo
### ✅ [Ссылка на публичную коллекцию в Postman](https://www.postman.com/flight-cosmonaut-70887455/workspace/demoshopping/collection/31214816-2bb3a8d5-1b28-4c22-b325-a0d0d600dbb7?action=share&creator=31214816)

Создана коллекция в Postman для тестирования SOAP-сервиса [CountryInfoService](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL), предоставляющего информацию о странах, валютах, языках и кодах.
## Протестированные методы сервиса
- `ListOfContinentsByName` - Получить список всех континентов
- `ListOfCurrenciesByName` - Получить список всех валют
- `ListOfCountryNamesByName` - Получить список стран по названию
- `CountryName` - Получить название страны по ISO-коду
- `CountryISOCode` - Получить ISO-код по названию страны
- `FullCountryInfo` - Получить полную информацию о стране
- `LanguageName` - Получить название языка по коду

