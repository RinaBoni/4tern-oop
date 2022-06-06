# 4tern-oop
## 1 практика
**Наследование, композиция, агрегация:**
  https://habr.com/ru/post/354046/
  
### 1. Что такое АДТ?
  
  АТД представляет собой тип данных, что означет следущее:
    наличие определенных доступных операций над элементами этого типа;
    данные, относительно которых эти операции выполняются (диапазон значений).
    
  
  Абстракция – это выделение и придание совокупности объектов общих свойств, которые определяют их концепутальные границы и отличают от всех других видов объектов. Иными словами, абстракция позволяет “пролить свет” на нужные нам данные объектов и, при этом, “затенить” те данные, которые нам не важны. (Гради Буч)
    
  
  АТД – это такой тип данных, который скрывает свою внутреннюю реализацию от клиентов. Удивительно то, что путем применения абстракции АТД позволяет нам не задумываться над низкоуровневыми деталями реализации, а работать с высокоуровневой сущностью реального мира (Стив Макконнелл).
    
### 2. Что такое предусловия?Для чего нужны? Что такое постусловия? Что такое класс? Что такое объект?
    
  ***Предусловие*** 
      
   Каждой из функций "требует" перечисляются условия, которым должны удовлетворять аргументы функции, чтобы входить в ее область; 
        Булевское выражение, которое определяет область функции, называется предусловием соответствующей частичной функции
        Нужно для введения коректных данных
        
  ***Постусловие*** 
    
  <sub>abstract RATIONAL mult [a,b]</sub>
  
  <sub>RATIONAL a,b;</sub>
  
  <sub>postcondition mult[0] = a[0]*b[0]</sub>
                 <sub>mult[1] = a[1]*b[1]</sub>
                    
   Постусловие указывает, что делает операция. В пост-условие, используется имя функции (в данном случае mult) для обозначения результата операции. Таким образом, mult [0] представляет числитель результата и множитель 1 представляет знаменатель результат. То есть указывает, какие условия становятся истинными после того, как выполняется операция. В этом примере пост-условие указывает что числитель результата рационального умножения равен целое произведение числителей двух входов и знаменателя равно целому произведению двух знаменателей.
      
  ***Класс***
  
  В объектно-ориентированном программировании (ООП) — класс это основной элемент, в рамках которого осуществляется конструирование программ. Класс содержит в себе данные и код, который управляет этими данными.

   Класс зачастую описывает объект реального мира. Как и реальный объект, класс содержит свой набор параметров и характеристик. Каждый такой параметр называется поле класса (очень похоже на обычные переменные). Также класс способен манипулировать своими характеристиками (полями) с помощью методов класса (похожи на функции в процедурных языках).
      Следует понимать, что класс — это каркас, иначе говоря, описание реального объекта. На основе этого «описания» создаются экземпляры реального объекта. 

  ***Объект***
     
   Объекты — это сущности, у которых есть свойства и поведение. Обычно объекты являются экземплярами какого-нибудь класса. Например, в игре может быть класс Character (персонаж), а его экземплярами будут hero или npc.

### 4. Что такое абстрагирование?
### 5. Что такое инкапсуляция? Что такое метод, конструктор, оператор?
### 6. Что такое принцип сокрытия? Что такое «чёрный ящик»?
### 7. Что такое поле класса? Что такое свойство (C#)?
### 8. Как вызвать метод конкретного объекта находящегося в массиве? Чем отличаются обращения к методам в С++ с использованием объекта, ссылки на объект и указателя на объект?
### 9. Что такое равенство объектов? Когда объекты идентичны?
### 10. Что такое поведение? Что такое состояние?

Сделайте шпаргалку по выбранному в задании 1 языку программирования:
  характеристика и особенности языка; номер последней версии
  типы данных
  создание проекта консольного приложения и приложения с GUI в вашей любимой среде разработки
  подключение сторонних модулей
  использование (установка) библиотеки для модульного тестирования
  
## 1 лекция
  DRY, KISS, единственная отвественность,
  тип данных словарь
    пример: https://github.com/VetrovSV/OOP/blob/master/examples/cpp_map/main.cpp
    слайды: https://raw.githubusercontent.com/VetrovSV/OOP/master/OOP_2.pdf
