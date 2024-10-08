---
title: Функциональный анализ и модульный синтез
---

Каждая трудовая/профессиональная/проектная роль в силу специфики своих
предметов интереса видит частное описание системы как «прозрачного
ящика», состоящее из интересующих её видов частей, позволяющих обсудить
её предметы интереса. «Операционный менеджер»::роль, например, по поводу
системы интересуется не тем, как система работает (функциональным
описанием), но «из чего собрано» (конструктивы) и логистикой этих
конструктивных частей к месту сборки, а после сборки --- к месту
продажи. У операционных менеджеров нет предмета интереса
«функциональность системы», но у них интерес к конструкции системы, они
будут управлять конфигурацией, «чтобы ничего не потерялось, всё
собралось и ничего не перепуталось». Менеджмент/management --- это
обычно не про функциональность, это про логистику! Это про «в срок,
вовремя, ничего не потеряно, всё передано из рук в руки, выполнены все
предложенные инженерами работы». Предметом операционного менеджмента как
метода работы операционного менеджера будут конструктивные части,
претерпевающие изменения их состояний в ходе работ создателей.

А вот инженер-разработчик, думающий над расчётом режима
работы/функционирования/операций какой-то системы, думает сначала над
«как работает» (**функциональный анализ** на основе функциональной
декомпозиции) система, чтобы из взаимодействия функциональных
частей-подсистем появлялась/emerge нужная функция целой системы, а потом
он обязательно будет решать «из чего собрать» (**модульный
синтез/сборка,** подбор аффордансов-конструктивов из конструктивного
разбиения для функциональных частей системы). Модульный синтез у
инженера-разработчика будет не сразу, но когда разработчик в ходе
функционального анализа поймёт, какие именно там операционные/рабочие
режимы времени эксплуатации, какие характеристики потребуются от
подсистем, чтобы подобрать необходимые аффордансы конструктивов/модулей.

«Функциональный синтез» говорить не принято. Говорят именно про
функциональную декомпозицию и функциональный анализ (анализ --- это тоже
«дробление»). В анализе берём функциональный объект (роль) в надсистеме,
и ищем его декомпозицию/разбиение на подсистемы, тоже функциональные
объекты. А для конструктива как материального объекта --- берём самые
разные материальные объекты-конструктивы (материальность тут
подчёркивает существование и вне времени эксплуатации системы, но и во
время создания, и даже вне проекта --- «самих по себе») и ищем в них
аффордансы/подходяшки, чтобы собрать из этих аффордансов-конструктивов
такой надконструктив, который сможет «сыграть требуемую роль»/«воплотить
функциональный объект» во время использования. То есть вроде как
конструктивы синтезируем/собираем из материальных частей, а
функциональные объекты, наоборот, только дробим --- это логическое
описание метода. В жизни всё это происходит итеративно и с разными
догадками, довольно долгое время, ибо оптимизация же, итеративный
процесс, да ещё и на многих проектах, многих версиях системы. Особо
заметим, что и функциональный и конструктивный объекты --- это виды
физических объектов. Разве что функциональный объект физический тогда,
когда его роль играет конструктивный материальный объект (то есть
материал для физичности функционального объекта берётся не «ниоткуда», а
именно из материального объекта, который поставлен играть роль,
выполнять назначенную функцию).

Обратите внимание, что в инженерии обязательно присутствуют и
функциональный/системный анализ (системы обычно описывают прежде всего
по их ролям, функциям --- поэтому функциональный и системный анализ
синонимичны), и модульный синтез. **У** **нас** **курс** **полного**
**системного мышления, в котором анализу и синтезу уделяется равное
внимание.** **Это не курс** **только** **системного анализа, весьма
небольшой и ограниченной части системного мышления!**

Те, кто занимается только анализом (функциональным/системным или
каким-то другим) --- это мечтатели, которые не имеют шанса изменить мир.
Мир-то нужно менять физически. Для этого нужно, чтобы какие-то
конструктивы/продукты/модули начали воплощать функциональные части
системы, то есть физически были собраны так, чтобы начать
взаимодействовать. Мало понимать, как система работает, думать о
системе, обсуждать систему, анализировать её --- система должна быть
воплощена в физическом мире, для этого надо выполнить модульный синтез,
то есть сконструировать/спроектировать конструкцию системы из
конструктивов, изготовить конструктивы, собрать из них систему, отладить
её работу, дальше развивать эту систему, выпускать множество постоянно
улучшаемых версий системы. Это всё работа «синтетиков», а не
«аналитиков». Инженер --- это тот кто думает и делает, а не только
аналитик, который только думает и с работами по изменению мира никак не
связан.

Это ровно то же рассуждение, что про исполнителей человеческих ролей в
спектаклях. Если только писать пьесы, прописывать хорошо роли и их
поведение, но не думать про воплощение этих пьес актёрами (в том числе
роботами, в том числе животными!), то можно смело считать, что это
просто художественная литература, а не драматургия. Актёры там будут
летать, растворяться в воздухе, реплики давать телепатически: если не
доходить мыслью до реальности, то можно всё! Драматург и режиссёр пьесы
обычно представляют, что их пьеса будет жить в реальности, играться на
весьма ограниченной в пространстве сцене весьма ограниченное время, а
зрителей в зрительном зале будет тоже ограниченное количество --- и
зрителям никак не передашь мысли и переживания персонажей, как это можно
сделать в художественной литературе, просто дав описания. Нет, надо всё
выразить средствами актёрской игры, на это и драматургия, написание
сценариев пьес, а не просто «писательство» как таковое.

Инженерное мышление не должно быть только аналитично, умозрительно, оно
должно быть адекватно, то есть не терять связи с физическим миром, не
витать только в облаках, выходить на изменение мира к лучшему, к
созданию и развитию систем, мало только объяснять мир, анализировать
системы!

Поэтому системный мыслитель не ограничивается только временем
функционирования, но занят ещё и временем разработки. Он обязательно
выделяет не менее четырёх областей/зон интереса (и это только начало,
обычно этих зон/областей интереса больше, и в каждой по множеству
предметов интереса):

-   функциональную/ролевую,
-   конструктивную/материальную/модульную
-   пространственную (совмещения функциональной и конструктивной в
    рамках 4D экстенсионализма, отношение реализации проявляется в том,
    что функциональные и конструктивные части занимают одно и то же
    пространство-время, поэтому пространство-время вводится явно)
-   стоимостную/затратную/экономическую/ресурсную.

**Анализ/декомпозиция всегда только часть мышления! Опасайтесь проекта,
где непонятно кто принимает решения по синтезу! Синтез меняет мир,
анализ не меняет мира!** **Только решения по синтезу меняют мир!**

**Кто имеет право указать, что в ракете будет три ступени? Что в
предприятии будет три подразделения? Что Вася Пупкин будет играть роль
Принца Гамлета, а Даша Неврубкина не будет? Это точно не аналитики!**
**Это инженеры, которые меняют мир, а не только понимают мир!**

«Аналитик» тут --- роль, а не должность. Агент (человек или даже целая
организация) на должности «аналитик» вполне может выполнять и роль
аналитика, и роль синтетика/конструктора, то есть принимать решения и по
функциональной декомпозиции, функциональном анализу, и по модульному
синтезу. Но лучше бы назвать такую должность с принимающим решения по
поводу изменения мира человеком иначе, «инженер»: участники проекта не
ожидают от «аналитиков» полномочий по изменению мира и поэтому не
склонны обсуждать с людьми на должности аналитиков решения по модульному
синтезу.

Обычно такие решения по назначению конструктивных частей системы на
ролевые/функциональные части делает инженер-проектировщик, опираясь при
этом на принципы разбиения системы на конструктивные части и описание
связи этих конструктивных частей, которые готовит инженер-архитектор
(это основная часть работ по созданию концепции системы --- назначение
конструктивов-аффордансов на роли подсистем). Аналитик тем самым ---
только часть инженера-проектировщика и часть инженера-архитектора.
Отдельный аналитик сегодня считается больше «испорченным телефоном»
между внешним миром и инженером, который принимает решение. Как вы яхту
назовёте, так она и поплывёт. Переобзовите аналитика инженером, и вы
увидите, как он начнёт брать на себя ответственность за принимаемые
решения (а не только за аналитическое «понимание» и «найденные
проблемы»), а окружающие его люди будут признавать эти решения, а не
считать, что это только «рекомендации аналитика» для какого-то инженера.
Подробней об этом рассказывается в курсах «Системная инженерия» и
«Системный менеджмент».

«Инженер предприятия»/менеджер::роль для «инженерии предприятия»/
менеджмента::метод. Орг-проектировщики и орг-архитекторы/«архитекторы
предприятия» понимают, что они по сути своей --- инженеры
организаций::система (иногда так и говорят: организационных систем).
Иногда орг-проектировщики и орг-архитекторы прямо называют себя
инженерами предприятия, чтобы отличить себя от «просто менеджеров», имея
ввиду, что они не «операционные менеджеры» и занимаются не методами
operations time предприятия, то есть что они не «операторы предприятия»
и не занимаются администрированием, но создают и развивают предприятие.
Помним, что MBA --- это степень master of business administration,
менеджмент в разговоре сводят к администрированию. Орг-разработчики и
орг-проектировщики подчёркивают при этом, что они в инженерии
предприятия пользуются стандартами системной инженерии, относясь к
организации как системе.

Лидеры (те, кто проводят организационные изменения, аналоги
инженеров-технологов в машиностроении, то есть «специалисты по
изменениям физического мира, изготовлению воплощения системы») берут у
орг-проектировщиков и орг-архитекторов концепцию организации
(специализация концепции системы для орг-системы: решения по
реализации/воплощению оргролей оргзвеньями с учётом орг-архитектурных
решений) и дальше «изготавливают» само предприятие по этим описаниям,
разъясняя оргроли из функционального описания организации агентам на
каждой должностной позиции в оргструктуре как конструктивном разбиении
организации. Лидеры «катализируют сотрудничество» путём создания
атмосферы, где каждый агент-сотрудник качественно исполняет свои роли,
где бы ни находилось его рабочее место (описание размещений) и с кем бы
ни приходилось этим агентам-сотрудникам общаться в условиях неизбежности
продуктивных конфликтов между интересами играемых агентами-сотрудниками
ролей.

Конечно, это всё подробно рассказывается в курсе «Системный менеджмент»,
тут же нам надо только подчеркнуть, что **концепцию организации лидеры**
**берут у** **орг-проектировщиков и** **орг-архитекторов, то есть**
**у** **«синтетиков»,** **а не аналитиков, а** **если концепции
организации нет, то лидерам буквально нечего делать ---** **если нет
оргпроекта, непонятно, что объяснять сотрудникам в части разделения
труда в проекте**. Орг-аналитика выполняется по необходимости самими
людьми, выполняющими инженерные роли орг-проектировщиков и
орг-архитекторов. Какой-нибудь «начальник отдела», организующий свой
отдел, выполняет роли орг-проектировщика и лидера (вместе эти роли можно
объединить в роли «менеджера оргразвития»), а также орг-архитектора
этого отдела, и ещё может выполнять роли в проекте прикладной инженерии
«его системы» (для него это будет «наша система», иногда даже
совпадающая с целевой), например, архитектора системы --- чем меньше
предприятие, тем больше ролей играет один и тот же агент.

И, конечно, «функциональный анализ» и «модульный синтез» --- это только
два аспекта в описании системы. В инженерии (целевой системы, личности,
предприятия, сообщества) нужно при анализе и синтезе разбираться со
всеми основными (четырьмя или даже пятью) аспектами, и даже большим
числом аспектов --- ибо кроме основных могут быть и другие. Системное
мышление как раз про то, как найти субоптимальное решение синтеза (как
функцию воплотить конструкцией, как-то скомпонованной в пространстве и с
затратами не выше тех, которые готовы платить внешние проектные роли, а
также работами, которые возможно выполнить с имеющимися ресурсами в
обозримые сроки), устраивающее все проектные роли.

Оптимума в синтезе всё равно не получите, субоптимальных (то есть
заведомо хуже оптимальных, «наименее плохих из всех нам известных», а не
«лучших из известных хороших») решений всегда множество примерно одного
качества на базе SoTA идей (помним про неустроенности от конфликтов
между системами разных системных уровней), вы должны догадаться хотя бы
о некоторых субоптимальных решениях, выбрать одно из них. Рациональный
выбор проектного решения среди предложенных в ходе синтеза часто тоже
называют «анализом», при этом есть ресурсное ограничение на этот выбор
решения для синтеза --- избегаем analysis
paralysis^[<https://en.wikipedia.org/wiki/Analysis_paralysis>].

Системный/модульный синтез --- это всегда многокритериальная
оптимизация, которая идёт сразу на многих системных уровнях, в основе её
лежат **догадки/гипотезы/изобретения**, которые прошли многочисленные
обоснования. **Если вам удалось более глубоко согласовать все описания**
**по всем основным видам** **разбиений** **проектируемой системы,** **и
даже добавить какие-то дополнительные виды,** **большой шанс, что у вас
будет** **(временный, только на текущий момент)** **успех по сравнению
со всеми конкурентами, которые учтут описание по меньшему числу
аспектов.**
