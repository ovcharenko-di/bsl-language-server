# Одно выражение в одной строке (OneStatementPerLine)

|      Тип      |    Поддерживаются<br>языки    |     Важность     |    Включена<br>по умолчанию    |    Время на<br>исправление (мин)    |             Теги             |
|:-------------:|:-----------------------------:|:----------------:|:------------------------------:|:-----------------------------------:|:----------------------------:|
| `Дефект кода` |         `BSL`<br>`OS`         | `Незначительный` |              `Да`              |                 `2`                 |    `standard`<br>`design`    |

<!-- Блоки выше заполняются автоматически, не трогать -->
## Описание диагностики

Тексты модулей оформляются по принципу "один оператор в одной строке". Наличие нескольких операторов допускается только для "однотипных" операторов присваивания, например:

`НачальныйИндекс = 0; Индекс = 0; Результат = 0;`

## Источники

* [Стандарт: Тексты модулей](https://its.1c.ru/db/v8std#content:456:hdoc)

## Сниппеты

<!-- Блоки ниже заполняются автоматически, не трогать -->
### Экранирование кода

```bsl
// BSLLS:OneStatementPerLine-off
// BSLLS:OneStatementPerLine-on
```

### Параметр конфигурационного файла

```json
"OneStatementPerLine": false
```
