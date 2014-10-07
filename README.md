CourseWork-OOP2014
==================
Това беше заданието, по което писах този проект. Финалната част от курса "Обектно-ориентирано програмиране", воден от доц. А. Семерджиев, СУ ФМИ, 2014г.

                                       Описание на проекта

Вашата задача е да напишете компютърна игра, в която управлявате герой, който може да 
се движи по двуизмерна карта, да събира различни предмети и да влиза в схватки с различни 
чудовища. С цел улесняване на проекта, не е задължително в играта да са заложени различни 
мисии, които героят да изпълнява. Като минимум играта трябва да отговаря на дадените по-
долу изисквания, като сами можете да уточните детайлите по тях.

	Герой

Героят в играта трябва да има различни характеристики, като например сила, живот, мана и 
пр. Сами можете да определите какви да бъдат характеристиките, но като минимум:

- Героят трябва да има характеристика живот, която може да се променя в рамките на играта. Ако тази характеристика стане нула, играта приключва.

- Характеристиките трябва да се използват за определяне на изхода от схватките. Сами можете да определите схемата, по която да се провеждат те. Например героят може да има оценки за сила, ловкост и защита, които да се сравняват с тези на противника по време на атака, за да се определи дали тя е успешна.

- Идея за допълнителен бонус:
  В играта може да се добавят магически умения, които героят да 
използва в различни ситуации.

        Предмети

В рамките на играта, героят трябва да може да събира, носи и използва различни предмети. Сами можете да изберете какви да бъдат предметите и дали героят трябва да има лимит за това колко/какви предмети може да носи.

- Идея за допълнителен бонус: В рамките на проекта не е задължително героят да може да се екипира с намерените предмети (напр. да носи определен меч, щит, шлем и пр.), но ако това бъде реализирано, трябва да се определи по какъв начин екипираните предмети ще влияят на 
играта (напр. как екипираното оръжие влияе на изхода от схватките).

        Карта

Играта трябва да се състои от различни нива, по които героят може да се придвижва. 
- Всяко ниво представлява двуизмерна карта, подобна на шахматна дъска, но с произволен размер.

- Героят трябва да може да се придвижва нагоре, надолу, наляво или надясно по картата. 

- Клетките на картата могат да бъдат проходими или непроходими (например стена).

Като минимум, интерфейсът на играта трябва да показва картата и положението на героя върху нея. Сами можете да изберете какви символи да използвате за визуализиране на картите. 

- Между отделните нива трябва да има преходи, които могат да бъдат или да не бъдат отбелязани на картата. 

        Файлове

Информацията за нивата трябва да се пази в един или повече файлове и да се зарежда когато е необходима (например когато се зарежда ново ниво). Сами можете да изберете формата, в който да описвате нивата (напр. може да използвате текстов файл, чието съдържание съответства на визуализацията на нивото и който можете лесно да редактирате).
Играта трябва да позволява да се записва текущото състояние (характеристики на героя, докъде е стигнал, какви предмети носи и т.н.) 

Реализирайте валидация на данните при четене.
