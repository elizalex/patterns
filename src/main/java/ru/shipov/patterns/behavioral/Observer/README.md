Наблюдатель (Observer)
-------------------------
  Поведенческий шаблон проектирования. Реализует у класса механизм, который позволяет объекту этого класса получать 
  оповещения об изменении состояния других объектов и тем самым наблюдать за ними.
  
Назначение
-------------------------
 Определяет зависимость типа один ко многим между объектами таким образом, 
 что при изменении состояния одного объекта все зависящие от него оповещаются об этом событии.
 
 Реализация
 -------------------------
 ![Observer](https://upload.wikimedia.org/wikipedia/commons/8/8a/Observer_UML.png)

Плюсы
-------------------------
 - расцепленная связь между субъектом  и наблюдателем;
 - поддержка транслирования.
 
 Применение
 -------------------------
 Шаблон «наблюдатель» применяется в тех случаях, когда система обладает следующими свойствами:
 - существует как минимум один объект, рассылающий сообщения;
 - имеется не менее одного получателя сообщений, причём их количество и состав могут изменяться во время работы 
 приложения;
 - позволяет избежать сильного зацепления взаимодействующих классов.
 
 Данный шаблон часто применяют в ситуациях, в которых отправителя сообщений не интересует, 
 что делают получатели с предоставленной им информацией.

 [на главную страницу](https://github.com/EvgeniyShipov/patterns)