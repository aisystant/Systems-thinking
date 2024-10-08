---
title: Форматы описания системных уровней
---

Системные уровни состоят из иерархии по отношению
часть-целое/composition. Эти иерархии вроде как удобно изобразить
картинкой графа-«дерева», вроде той, которую мы только что обсуждали в
связи с именованием систем по отношению к целевой системе. Для
иллюстративных целей это подходит, для работы --- нет. Графические
модели крайне неудобны в редактировании, в изменении. При разработке
системных разбиений, их согласовании в команде проекта вам нужно будет
быстро (это ключевое) менять варианты системного разбиения. Для этого мы
предлагаем использовать «аутлайн», текстовое представление дерева
иерархии, где каждый уровень представляется отступом.

Вот предыдущая картинка как аутлайн, проставлены те же цифры, что и на
картинке:

Надсистема (1)

Система в окружении

Система в окружении (3)

Целевая система (2)

-   Подсистема
-   Подсистема (4)
-   подсистема

Конечно, эти именования (как и любая терминология) более-менее условны.
Так, в ТРИЗ надсистема так и называется --- надсистема, а англоязычные
системные инженеры обычно слово «надсистема» не говорят (очень редко
не-инженеры говорят suprasystem, но не supersystem), хотя и говорят
«подсистема» (subsystem).

В основополагающем стандарте системной инженерии ISO 15288:2023 вообще
не говорят обо всех этих видах систем, подчёркивая их одинаковость:
различают только целевую систему (system-of-interest) как вершину
системного разбиения. «Выше по системным уровням» идут сразу «системы в
окружении», которые рассматривают вообще отдельно, включая саму
надсистему. В составе целевой системы в этом стандарте только системы
(если у этих систем будут части) и системные элементы (elements, если
было принято решение не рассматривать их части, а только ограничиться
существованием этих системных элементов как целых, являющихся частями их
надсистем).


![](07-formats-for-describing-systems-levels-33.png)


Дадим эту картинку как многоуровневый список/аутлайн, заодно переведя на
русский:

Целевая система

Система

Элемент системы

Элемент системы

Система

Система

-   Элемент системы
-   Элемент системы
-   Элемент системы

Элемент системы

Элемент системы

Система

Элемент системы

Элемент системы

Система

Система

-   Элемент системы
-   Элемент системы

Элемент системы

Система

-   Элемент системы
-   Элемент системы

Элемент системы

Картинка и текст тут примерно одинаковой наглядности, ибо представлено
очень немного элементов в системном разбиении. Теперь представьте, что
нужно изобразить 500 элементов (масштаб проблемы: в авиалайнере или
ледовой буровой платформе 5-6 миллионов элементов). Диаграмма-картинка
сразу будет помещаться только на многих сложно сопоставляемых друг с
другом страницах, она не влезет ни на один компьютерный монитор, а если
её бить на части, будет абсолютно нечитаема. Правки в этой диаграмме
будут очень долгими и многие правки будут вести к ошибкам.

Текстовый вариант с аутлайном легко править, он легко вытягивается в
просто «длинный текст» (люди привыкли работать с многостраничными
текстами, используя скроллирование), длинные имена свободно помещаются в
строку (даже ещё можно и комментарии давать!). Так что используйте для
работы с системными разбиениями аутлайны/outlines/«nested
lists»/«многоуровневые списки».

Альтернативный способ --- это использовать явную нумерацию уровня как
отдельный элемент списка. Вот та же структура, что в предыдущем списке,
только представлена в табличной форме (например, Excel таблице). Целевая
система как целая при этом в нашем варианте представления не имеет кода,
а число позиций в коде --- это системный уровень (1.3.1.1. --- это будет
четвёртый уровень, если целевая система на нулевом уровне. Как ни
печально, но в стандарте ISO 15288 на картинке опечатка в нумерации
уровней, четвёртый уровень показан как пятый!)

+-----------------------------------+-----------------------------------+
| Код системы                       | Имя системы                       |
+-----------------------------------+-----------------------------------+
|                                   | Целевая система                   |
+-----------------------------------+-----------------------------------+
| 1.                                | Система                           |
+-----------------------------------+-----------------------------------+
| 1.1.                              | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 1.2.                              | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 1.3.                              | Система                           |
+-----------------------------------+-----------------------------------+
| 1.3.1.                            | Система                           |
+-----------------------------------+-----------------------------------+
| 1.3.1.1.                          | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 1.3.1.2.                          | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 1.3.1.3                           | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 1.3.2.                            | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 1.3.3.                            | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 2.                                | Система                           |
+-----------------------------------+-----------------------------------+
| 2.1.                              | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 2.2.                              | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 2.3.                              | Система                           |
+-----------------------------------+-----------------------------------+
| 2.3.1                             | Система                           |
+-----------------------------------+-----------------------------------+
| 2.3.1.1                           | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 2.3.1.2                           | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 2.3.2.                            | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 2.3.3.                            | Система                           |
+-----------------------------------+-----------------------------------+
| 2.3.3.1.                          | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 2.3.3.2                           | Элемент системы                   |
+-----------------------------------+-----------------------------------+
| 3.                                | Элемент системы                   |
+-----------------------------------+-----------------------------------+

Конечно, в этом примере таблицы «система» и «элемент системы» --- это
типы (из мета-мета-модели, типы важных объектов системного подхода) тех
объектов, которые будут заданы в таких таблицах или типами мета-модели
«из учебника предметной области», или даже типами мета-модели
предприятия, или даже для конкретного экземпляра системы --- именами
конкретных физических объектов. То есть в таблице будет стоять не
«система», «система», «система», а для автомобиля «шасси», «левое
колесо», «двигатель», для парусника «корпус лодки», «мачта», «грот» и
т.д.

Каждый раз используйте перевод графических представлений в иерархии, а
иерархии представляйте затем в таблицах --- иначе вы не справитесь с
сопровождением, не сможете вносить многочисленные изменения. Форматы
должны быть удобны не для «представления», а изменения: описания систем
(в том числе описание системных разбиений) --- это предмет непрерывных
переговоров в команде проекта, а поэтому --- предмет непрерывных
изменений. Форматы подгоняются под удобство изменений, всяческая
«наглядность» простых примеров «из учебника» и «из стандарта» не должна
отвлекать: учебники и стандарты вам не надо менять, изображения из них
вам не надо разбивать на много страниц. Используйте табличные
представления (в том числе и для работы с системными разбиениями), это
будет удобно.
