# База данных музея
  Для построения базы данных выбран крупнейший музей Воронежской области - Государственное бюджетное учреждение культуры Воронежской области «ВОРОНЕЖСКИЙ ОБЛАСТНОЙ КРАЕВЕДЧЕСКИЙ МУЗЕЙ». 
  Воронежский обласной краеведческий музей является объединением нескольких площадок с различной направленностью экспозиции:
  * Основное здание - здесь проходят экскурсии на тему истории воронежского края, археологических находок, а также проходят тематические выставки.
  * Арсенал - отдел краеведческого музея, посвященный истории ВОВ 1941-1945 годов.
  * История создания российского флота - музей расположен на действующем корабле Петровской эпохи "Гото Предистинация"
  * Дом-музей Дурова - отдел музея посвящен истории жизни артиста цирка А.Л. Дурова и истории цирка.
  Также в состав музея входит отделение "Фонды", которое расположено в историческом здании и является служебным зданием музея.
# О посещении музея
  * 9 мая 2023 года вместе с семьей в очередной раз посещали отделение краеведческого музея "Арсенал", где собраны экспонаты, связанные с историей великой отечественной войны. В нем собраны документы, монеты, медали, предметы быта, предметы одежды, оружие и боеприпасы времен ВОВ и связанные с ней. Также в экспозиции присутствуют диорамы, отражающие отдельные события войны на Воронежском фронте.
  * 9 августа 2023 года также в очередной раз удалось посетить сразу 2 выставки: осмотреть постоянно действующую экспозицию, посвященную истории Воронежского края от эпохи палеолита до нынешних дней, в "Основном здании" музея, а также посетить корабль "Гото Предистинация" и осмотреть постоянно действующую экспозицию, посвященную появлению и развитию Российского флота.
  * ![Текст с описанием картинки](/images/picture.jpg)
![Основное здание музея](/PHOTO/1.jpg)
![Внутри музея](/PHOTO/2.jpg)
![Гото Предистинация](/PHOTO/3.jpg)
![Внутри корабля](/PHOTO/5.jpg)
# Структура музея
  * Музей состоит из отделений;
  * Каждое отделение может содержать несколько залов;
  * В каждом зале представлены экспонаты, разделенные тематикой;
  * Движение по залу осуществляется по часовой стрелке, позволяя проводить осмотр от прошлого к настоящему;
  * Экспонаты, не участвующие в экспозиции находятся в хранилище;
  * Экспонаты разделяются по критерию принадлежности к "коллекции" - предмет быта, оружие, археологическая находка, документ и т.д.
# Работа музея
  * Есть расписание экскурсий;
  * Есть перечень выставок;
  * Выставки могут быть организованы на территории музея или на выезде;
# О базе данных
  База данных должна решать следующие задачи:
* Для посетителя:
    * Нахождение нужного отделения для посещения с учетом названия выставки, экскурсии или конкретного экспоната;
    * Запись в группу для посещения с учетом расписания экскурсий, названий выставок;
* Для работников и администрации:
    * Учет сотрудников;
    * Формирование графика работы сотрудников;
    * Контроль посещений;
    * Контроль и учет экспонатов по статусам;
    * Поддержание экспонатов в надлежащем состоянии;
    * Организация мероприятий;
    * Контроль проведения мероприятий.
    База данных по характеру использования состоит из основных сущностей:
    * Музей (это отделения, сотрудники)
    * Экспонаты (их расположение, параметры, движение, тематика)
    * Выставки (их тип, расписание, состав и т.д.)
    * Экскурсии (график, тематика и т.д.)


 
