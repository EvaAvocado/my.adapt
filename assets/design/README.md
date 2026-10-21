# Диаграммы ЛР 3

Основной отчёт: [docs/design/report.md](../../docs/design/report.md).

| Рисунок | Модель | Изображение | Редактируемый исходник |
|---|---|---|---|
| 1 | UML Activity — обычный игровой раунд | [PNG](01-gameplay.png) | [PlantUML](01-gameplay.puml) |
| 2 | UML Sequence — соревновательный раунд и рейтинг | [PNG](02-leaderboard-sequence.png) | [PlantUML](02-leaderboard-sequence.puml) |
| 3 | ER — логическая структура данных | [PNG](03-data-model.png) | [PlantUML](03-data-model.puml) |
| 4 | C4 Container — архитектура | [PNG](04-containers.png) | [PlantUML](04-containers.puml) |
| 5 | UML Activity — AS-IS | [PNG](05-as-is.png) | [PlantUML](05-as-is.puml) |
| 6 | UML Activity — TO-BE | [PNG](06-to-be.png) | [PlantUML](06-to-be.puml) |

Для воспроизведения использованы Java 21 и [PlantUML 1.2026.9](https://github.com/plantuml/plantuml/releases/tag/v1.2026.9). Исходники имеют кодировку UTF-8. C4-PlantUML включается из стандартной библиотеки PlantUML; для графовой компоновки используется встроенный Smetana. Отдельная установка Graphviz и передача содержимого внешнему серверу не требуются.

Команда из корня репозитория после загрузки plantuml.jar:

```powershell
java -Djava.awt.headless=true -jar "путь/к/plantuml.jar" -charset UTF-8 -tpng "assets/design/*.puml"
```

В отчёт вставлены готовые изображения: для чтения в Obsidian или GitHub установка PlantUML не требуется.
