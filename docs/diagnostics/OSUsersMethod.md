# Использование метода ПользователиОС (OSUsersMethod)

|            Тип             |    Поддерживаются<br>языки    |  Важность   |    Включена<br>по умолчанию    |    Время на<br>исправление (мин)    |     Теги     |
|:--------------------------:|:-----------------------------:|:-----------:|:------------------------------:|:-----------------------------------:|:------------:|
| `Потенциальная уязвимость` |             `BSL`             | `Критичный` |              `Да`              |                `15`                 | `suspicious` |

<!-- Блоки выше заполняются автоматически, не трогать -->
## Описание диагностики
<!-- Описание диагностики заполняется вручную. Необходимо понятным языком описать смысл и схему работу -->
Использование метода может нести вредоносную функцию ("Закладку").

## Источники
<!-- Необходимо указывать ссылки на все источники, из которых почерпнута информация для создания диагностики -->

Полезная информация: [Атака Pass-the-hash](https://ru.wikipedia.org/wiki/%D0%90%D1%82%D0%B0%D0%BA%D0%B0_Pass-the-hash)

## Сниппеты

<!-- Блоки ниже заполняются автоматически, не трогать -->
### Экранирование кода

```bsl
// BSLLS:OSUsersMethod-off
// BSLLS:OSUsersMethod-on
```

### Параметр конфигурационного файла

```json
"OSUsersMethod": false
```
