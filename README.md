# Proj-3.2
Thanks God it worked out in the end

**Состав команды**: Галлямова Сабина, Зотова София, Чочия Вахтанг \
\
**Ссылка на карту:** https://vato2755.github.io/Proj-3.2/ \
\
**О городе:** Астрахань, столица одноименной области, население - 465 тыс чел. Основные сектора экономики - топливно-энергетическая отрасль, машиностроение (в упадке). До недавнего времени был единственным в России городом с примерно полумилионным населением без муниципального общественного транспорта. В городе более 700 ОКН. \
\
**Данные и источники:** границы районов города, полигоны зданий - OSM. Точки ОКН из задания. Сетка - собственная работа. \
\
**Методы:** подготовка слоев в QGIS (так и не удалось понять, как в питоне делать аналог spatial join), визуализация в web'е уже через питон. \
\
**Самое сложное:** отслеживание и исправление триллионов ошибок, причину которых установить при нашем уровне владения пространственным питоном было практически невозможно. Работа с гитхабом тоже была весьма сложной, интерфейс контринтуитивный, даже удаление и переименование файла требуют открытия самого файла и использования контекстного меню справа сверху, хотя гораздо удобнее было бы дать доступ к таким действиям из самого репозитория (а если удалять и изменять надо десятки файлов?). Внесение минимальных изменений в код переносит на недовеб-версию VS code, где отсутствует добрая половина функционала, а сохранить изменения так и не удалось, пришлось перезагружать питоновский файл. Словом, в конце создалось впечатление, что для достижения того же, что в QGIS можно сделать за несколько минут, пришлось потратить часы. Сайт тоже завелся не с первого раза, кто бы мог подумать, что никакие имена, окромя index.html, гитхаб не принимает. \
\
**Что получилось и чем гордимся:** минимальные требования задания удовлетворили, поиск вставили, костыльно окрасили сетку, и на том спасибо. Гордиться здесь нечем. \
\
**Что не получилось**: все остальное. Хроноплет не пожелал добывать данные из одного файла (поэтому пришлось делать грид в QGIS и переносить уже с стилизацией .GeoJson), поиск по точкам не заработал (наш поиск по итогу охватывает только здания), не удалось и сделать единый FeatureGroup, чтобы поиск охватывал все фичи на карте. Ряд костылей позволил скомпенсировать эти недостатки. Даже точки ОКН легли неровно, что вынудило вручную их перетаскивать для прикрепления с полигонами зданий, но на полное перетаскивание не хватало времени, поэтому часть так и осталась олицевторять церковь, доходный дом или что-то более пафосное посреди улицы. В целом опыт получился, мягко говоря, не из приятных
