Посредник (Mediator)
-------------------------
 Поведенческий шаблон проектирования, обеспечивающий взаимодействие множества объектов, формируя при этом слабую 
 связанность и избавляя объекты от необходимости явно ссылаться друг на друга.
  
Назначение
-------------------------
 Обеспечивает взаимодействие множества объектов, сформировав при этом слабую связанность и избавив объекты от 
 необходимости явно ссылаться друг на друга.
 
 Реализация
 -------------------------
 Создать объект, инкапсулирующий способ взаимодействия множества объектов.
 
 Посредник определяет интерфейс для обмена информацией с коллегами, 
 конкретный посредник координирует действия объектов коллеги. 
 Каждый класс коллег знает о посреднике, все коллеги обмениваются информацией только с посредником,
 при его отсутствии им пришлось бы обмениваться информацией напрямую. 
 Коллеги посылают запросы посреднику и получают запросы от него. 
 Посредник реализует кооперативное поведение, пересылая каждый запрос одному или нескольким коллегам.
 
 ![Mediator](https://upload.wikimedia.org/wikipedia/commons/e/e4/Mediator_design_pattern.png)

Плюсы
-------------------------
 - устраняется связанность между коллегами;
 - централизует управление;

 [на главную страницу](https://github.com/EvgeniyShipov/patterns)