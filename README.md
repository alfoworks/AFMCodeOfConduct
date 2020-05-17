# ALFO:MINE Git Code Of Conduct #
## Правила коммитов
### Основные правила
1. Префикс коммита - обязателен
2. Описания коммитов должны быть составлены по существу, желательно с описанием измененных вещей, если их достаточно много.
3. При необходимости, можно использовать два и более префика.
4. Коммиты, генерируемые гитом или другим ПО автоматически не попадают под эти правила. Менять их сообщения необязательно.

### Структура
```
[Префикс] <Сообщение>                             
```

| Префикс | Значение | Пример |
| ------- | -------- | ------ |
| **[FIX]** | Всё, что касается исправления багов | [FIX] Баг с отправкой пакета |
| **[FEATURE]** | Всё, что касается новых возможностей | [FEATURE] Таблисты |
| **[STYLE]** | Всё, что касается опечаток и форматирования | [STYLE] Залупка в MOTD сервера |
| **[REFACTOR]** | Всё, что касается рефакторинга | [REFACTOR] Переход на Kotlin с Java |
| **[ANY]** | Всё, что не подходит к предыдущему. | [ANY] Обновление Gradle | 
## Правила оформления репозиториев
В каждом репозитории должен быть `README.md` файл, описывающий проект, находящийся в этом репозитории, заполненный по следующему шаблону:
# Имя проекта (репозитория)
<описание>

**Основной язык** Основной, часто используемый язык проекта

(если Minecraft проект) **Направление**:  возможные варианты: плагин <Sponge/Spigot>, серверный мод, клиентский мод, полноценный мод

(если Minecraft проект) **Версия**: версия minecraft, под которую создается проект
