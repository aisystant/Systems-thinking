---
title: Описания и методы описания, модели и мета-модели
---

Описание/view каких-то аспектов системы состоит из одной или множества
отдельных **моделей** (models). Тут, конечно, «состоит из» не отношение
композиции для физических объектов, надеемся, что вы это уже отметили
для себя. Часто поэтому слова «состоит из» заменяют уклончивым
«группирует» (описание группирует модели), а в обратную сторону ---
«группируются в» (модели группируются в описание).

Модель --- это набор каких-то объектов (физических или
абстрактных/информационных), который ведёт себя в каком-то смысле похоже
на поведение моделируемого объекта, то есть описывает этот моделируемый
объект (необязательно моделируемым объектом будет система --- можно
моделировать что угодно, «объект --- всё, что является предметом нашего
рассмотрения»). Типы этих моделируемых объектов задаются мета-моделью и
берутся из теорий/объяснений метода описания/моделирования (viewpoint).
Модели могут быть самой разной степени формальности (вплоть до того, что
самые неформальные описания стандарты могут считать «не-модельными
описаниями», но мы так считать не будем).

Например, полное системное описание включает в себя «финансовое
описание»::view предприятия::создатель (и между описанием и описываемым
предметом отношение представления/representation, обо всём этого
говорилось в курсе «Рациональная работа»).

В финансовом описании можно в свою очередь выделить разные составляющие
его модели, нужные для ответа на разные вопросы интересующейся финансами
проектной роли:

-   баланс (balance),
-   отчёт о прибылях и убытках (profit and loss, P&L),
-   денежный поток (cash flow).

Если у вас есть только баланс, то вы не ответите на вопрос о
безубыточности работы предприятия, а если у вас отчёт о прибылях и
убытках и даже баланс, то вы не сможете обсудить кассовый разрыв без
наличия документов по денежному потоку. Одно описание для одной области
интересов (с несколькими предметами интереса), три разные модели для
трёх более узких областей, вплоть до отдельных предметов интереса
(конечно, предметы интереса/важные характеристики могут уточняться!).

Все эти решения о том, как детально, широко или узко рассматривать
какие-то важные характеристики системы --- субъективны и являются
результатом договорённостей в проекте. Но вот общие принципы достижения
таких договорённостей, что обсуждать --- вот это неплохо бы знать, чтобы
достигать таких договорённостей быстрее.

Каждая из моделей должна быть выполнена с использованием одной из
мета-моделей/meta-models/model kinds (это подробно обсуждалось в курсе
«Рациональная работа», когда говорили об онтологических описаниях),
причём каждая из мета-моделей устанавливает определенные языки, правила
и прочие **соглашения** **о** **моделировании** (например, о том, каким
объектам мы присваиваем какие типы мета-модели или мета-мета-модели и
как будем выбирать имена объектов и имена типов из длинных рядов
синонимов).

Так же как отдельные модели (models), отвечающие за уторговывание
какого-то интереса, объединяются в более полное описание (view),
отвечающее за уторговывание интересов в какой-то области интересов, так
и мета-модели (metamodels/model kinds), определяющие язык, правила и
приёмы моделирования, используемые при ролевых/тематических/видов
описаниях, объединяются в **методы** **описания** (viewpoints),
отражающие/frame предметы интереса (concerns) в областях интереса (area
of concern). Методы описания с их мета-моделями и прочими соглашениями о
моделировании описываются часто в специальном документе, который так и
называется: «соглашение о моделировании». Часто для моделей с какими-то
данными о реальном мире мета-модель называется «модель данных» (данные =
модель системы, модель данных = мета-модель системы).

Например, для финансового описания/view создающей системы-предприятия
нужно прежде всего выбрать один из «методов описания»/viewpoint --- РСБУ
(Российские стандарты бухгалтерского учёта) или МСФО (международные
стандарты финансовой отчётности). При составлении баланса (одна модель
финансового описания) и отчёта о прибыли и убытках (другая модель
финансового описания) нужно использовать мета-модели (соглашения по
тому, как делать модели) для этих видов моделей из какого-то одного
метода описаний --- либо РСБУ, либо МСФО.

И помним, что есть ещё и уровень мета-мета-модели (то, что
РСБУ::viewpoint --- это как раз использование материала из нашего курса
для присвоения типа, мы сказали, что РСБУ --- это метод описания,
использовали тип мета-мета-модели фундаментальной дисциплины, общий тип
для всех дисциплин. А РСБУ представляет собой мета-модель, метод
описания предметной/прикладной дисциплины).

Проще всего считать, что метод описания --- это набор условных
обозначений для многослойных карт-моделей, которые описывают территорию.

Напомним то, что вы уже знаете из курса «Рациональная работа»:

-   Карта --- это не территория, а модель территории. Ходят не по карте,
    а по местности. Но выбираете вы маршрут обычно по карте. Другое
    дело, что набор условных обозначений (viewpoint) не даст вам карту
    (view), её придётся делать самостоятельно, заниматься моделированием
    какой-то местности (domain). А потом генерировать несколько
    маршрутов походов по этой карте, критиковать их («вау, этот маршрут
    ведёт в болото! Не пойдём туда!»), выбирать согласно какой-то из
    теорий решений наилучший способ действий, наилучший маршрут (лучший
    метод работы), а затем ещё и заставить себя (да и уговорить других)
    пойти по этому маршруту, то есть кроме выбора метода ещё и сделать
    саму работу по методу. Это всё метафора, конечно, но вам нужно
    разобраться в этой метафоре. В любом случае, ваша мысль должна
    дотягиваться до реальной работы, для которой вы должны определить
    метод (стратегировать: понять метод в ситуации, когда метод
    неизвестен), в каждом методе есть его предметы метода из его
    предметной области, они даны в какой-то модели, а эта модель имеет
    свою мета-модель.
-   Есть несколько уровней абстрактности, они же мета-моделирования, от
    самой общей модели теории понятий (theory theory --- «всё есть
    объекты и отношения», это можно считать foundational ontology, не
    путать с «foundation model»/LLM) через мета-мета-модель как набор
    типов для объектов и отношений из фундаментальных методов мышления
    (в том числе набор типов системного подхода --- «система»,
    «окружение», «системный уровень», «создатель», и т.д.), затем
    мета-модель какой-то предметной области (в том числе менеджмент с
    его типами: орг-архитектура, органиграмма, выпуск/проход/throughput
    и т.д.), затем модель с её уже значениями (например, выпуск/проход 3
    сепульки в день на \$30). Конечно, этих уровней может быть и больше
    (например, можно выделить метаУ-модель, метаС-модель). По факту,
    есть территория (мир), карта (модель), мета-модель (карта карты, то
    есть система обозначений для domain), есть мета-мета-модель (карта
    карты карты, то есть система обозначений для системы обозначений
    карты, универсальная для всех систем обозначений, то есть для всех
    domain), и есть даже мета-мета-мета модель (система обозначений для
    системы обозначений для системы обозначений карты). В системном
    мышлении вы должны это всё удерживать и не путать. Если вы вдруг
    заговорите терминами мета-мета-модели (словами из нашего курса), то
    вас никто не поймёт. Обсуждайте не системы обозначений, а карту. Но
    сами вы в голове должны удерживать то, откуда пришли обозначения на
    карте, и откуда пришли обозначения того, что дано в таблице
    обозначений.
-   На любом из уровней абстракции вы можете или моделировать строго
    (карта в масштабе, с точными обозначениями в какой-то проекции) или
    не очень строго (детская карта, карта метро --- где важно донести
    плохо понимающим в картографии людям какую-то одну идею, а не иметь
    точную модель). В моделировании это выбор уровня формальности --- от
    формальности с учётом унивалентных оснований математики (они будут
    построже, чем основания математики, построенной на теории множеств,
    и подразумевают конструктивизм --- даже не theory theory с объектами
    и отношениями, а пока плохо определённую и крайне нераспространённую
    фронтирную теорию понятий с объектами и операциями их
    конструирования, подробней это затронем в следующем разделе нашего
    курса) до формальности былин и эпосов, когда вы от
    мета-мета-мета-модели (foundational ontology) на базе объектов и
    отношений вдруг переходите к рассуждениям по аналогии (скажем,
    прототипной теории понятий, когда фрукты определяются как «разные
    варианты яблок, всё более и более на яблоки не похожие»), concept
    blending и прочей уже не логике, а чуть ли не лингвистике. Люди
    всё-таки в основном используют быстрый и лёгкий режим мышления S1, а
    не трудный и неудобный режим мышления S2. Рассуждения в S1 трудно
    критиковать, они «аналоговы», а вот рассуждения в S2 критиковать
    легко --- там работает логика, и там либо вы правы, либо ошиблись.
    Если вам важна точность, то надо быть формальным: на неточных
    рассуждениях ракету не построишь, подлодка утонет, предприятие
    разорится. Но если вы будете только строгим логиком, то вы не
    сможете разговаривать с «простыми людьми».

В любом случае, **нельзя ничего описывать, если ты не осознал, как
именно ты описываешь, каким способом** **описания!** **Нельзя понять
чьё-то описание, если ты не осознал, как именно, каким способом описания
это чьё-то описание сделано!**

Нельзя делать карты и/или давать рассматривать другим проектным ролям
карты, если изготовителю карты и/или другим проектным ролям неизвестна
легенда карты и методы картографирования. Карты, сделанные по разным
методам описания, потом нельзя сопоставлять друг с другом. Нельзя делать
карту, используя слои, подготовленные согласно разным методам
картографирования --- нельзя брать подготовленную геодезистами карту
водных ресурсов города и подготовленную службами метрополитена
карту-схему станций метро и просто накладывать их друг на друга. Нельзя
брать баланс по РСБУ, а отчёт о прибылях и убытках делать в МСФО. Все
модели (models) из описания (view) должны быть подготовлены с
использованием мета-моделей из одного метода описания (viewpoint). И да,
метод описаний нужно согласовывать с проектной ролью, ибо в зависимости
от предмета интереса и предпочтений роли в характеристиках этого
предмета интереса разные проектные роли будут требовать использовать
разные методы описаний! Например, финансисты из бухгалтерии будут
требовать финансовые описания по МСФО (и у них важным будет описание
себестоимости), а операционные менеджеры будут отказываться от таких
описаний и настаивать на ведении собственного финансового учёта, потому
что они будут считать «себестоимость» вредной и сбивающей с толку
характеристикой, настаивая на совершенно других методах финансового
расчёта, более пригодных не для целей налогообложения, а для целей
операционного менеджмента. Они могли бы настаивать на использовании
методов описания, принятых в «учёте прохода»/«throughput accounting» из
теории ограничений
Голдратта^[<https://en.wikipedia.org/wiki/Throughput_accounting>].

Вопрос, а как же тут быть --- если всем нужны какие-то разные описания?
Как быть, например, в случае того же финансового учёта (для управленцев,
pre mortem) и бухгалтерского учёта (для налоговой инспекции, post
mortem?). Конечно, надо просто делать несколько разных описаний!
Описываемому предмету никак не помешает, если вы сделаете его фотографии
с разных ракурсов, разными фотокамерами, а иногда ещё и видеосъёмку, а
ещё и просветку в рентгеновских лучах, а потом ещё добавите описание
текстом в стихах.

Так, управленцы могут организовать СебеУчёт по Голдратту, а ТебеУчёт1 по
РСБУ (для своей налоговой) и ТебеУчёт2 по МСФО (например, для
акционеров). Это ОК, это нормально, так и надо делать --- только
приглядывать за тем, чтобы описывался один и тот же объект (деньги
предприятия и их движение), а не разные. Иногда говорят о правилах
соответствия (correspondence rules) между объектами разных описаний, но
эти правила соответствия не всегда возможно определить, тут не надо
обольщаться: соответствий между фотографией кипящего чайника в
инфракрасном свете и ведомостью комплектующих для изготовления чайника
может не обнаружиться. Но вот в разных инженерных моделерах могут
встретиться разные значки для отображения функционального объекта --- и
тут можно указать, что есть соответствие/correspondence, например, между
какой-нибудь functional block из DIN 66001 и functional module из IEC
61346. Конечно, для того, чтобы обнаружить такое соответствие, вы должны
подняться на мета-уровень по отношению к этим стандартам: понять, что
все эти объекты --- функциональные объекты, а не конструктивные или
объекты размещения (места).

Метод описания чаще всего бывает **библиотечным** (library), это
означает, что вместо раскрытия его содержания приводят просто ссылку на
литературу по этому методу. Это всё равно как вместо полного текста и
картинок легенды карты можно было бы просто дать ссылку на книгу или
картографический стандарт, где приведён список условных значков и
подробный текст о том, как использовать эти значки для изображения
деталей рельефа, флоры, фауны, полезных ископаемых, плотности населения
и т.д. Но если нет ещё текста с готовым методом описания, то вам
придётся описывать какой-то предмет интереса таким способом, который до
сих пор не использовался. Тогда вместо этой ссылки на библиотечный метод
описания вы обязаны к описанию приложить документированный вами самими
метод описания: без указания метода описания сами описания делать
нельзя. Метод описания --- это альфа, так что для свидетельствования
состояния этой альфы потребуется артефакт/рабочий продукт/документ. И
описание требует документирования, и метод описания требует
документирования.

Главное --- это запомнить: **любое описание ---** **это описание
системы, любое описание системы сделано с использованием метода
описания** (даже если описывающий этого не осознаёт), доступно людям
описание становится только после его **документирования**, метод
описания --- это описание описания (поэтому уместны вопросы и про метод
описания метода описания, и про документирование метода описания метода
описания!).

Метод описания (viewpoint) оформляет (frame) какую-то важную для
выполнения ролью какого-то метода работы характеристику (concern этой
роли). Одно из следствий: **если у** **проектной роли/stakeholder**
**нет соответствующей** **«озабоченности»/concern, то описание/view**
**для удовлетворения интереса к этой** **отсутствующей**
**характеристике** **не делается: описания,** **в которых не
затрагиваются** **важные для** **методов работы** **каких-то ролей**
**характеристики, не нужны, они избыточны.** Соответственно, это
описание не документируется, и метод описания для него тоже не нужен.

Даже если какой-то используемый вами регламент или стандарт (который
вроде бы надо исполнять) требует какого-то описания, но вы обнаружили,
что никто его никогда читать не будет (например, менеджеры просто
проверят факт наличия описания «для соответствия стандарту», но даже в
случае реализации каких-то рисков никто в эти описания не полезет
разбираться, их не откроет и не использует для разбирательств по
существу) --- такое описание не нужно делать, это бессмысленная трата
ресурсов проекта. И наоборот: **если** **проектной роли** **важна**
**какая-то** **характеристика/«предмет интереса»/concern** **и** **она
намерена её обсуждать с другими проектными ролями, или даже использовать
для собственного мышления и принятия ролевых решений,** **то описание**
**с включением этой** **характеристики** **делается** **и**
**обязательно** **документируется.** Речь никогда не идёт об устных
ответах на вопросы. На бумаге, или в базе данных, или в файлах, но
описание должно быть документировано.

Скажем, вы приняли какое-то решение на совещании. Это решение ---
описание будущей ситуации, какого-то состояния каких-то объектов. Не
записано (и не в протокол, ибо протоколы не выживают больше пары недель,
дальше они забываются) --- значит решение не принято, а просто
«обсуждено». Решение в письменном виде наверняка будет иным, нежели всем
«послышалось» как оно звучит устно, там будут обнаружены ошибки,
несоответствия другим ранее принятым решениям и т.д. Описания --- это
отнюдь не только предписанные в каком-то инженерном или менеджерском
стандарте описания! Надо очень жёстко отличать системы (и ситуации, то
есть системы в каких-то состояниях, учитывающие происходящие с ними
изменения состояний) и описания систем, а также выполнять все требования
к описаниям, какие бы они ни были. Например, решение на совещании: если
это описание (view), то там обязательно должен быть и метод описания
(viewpoint). Что именно вы описываете, какие типы основных объектов
будут в вашем описании решения совещания?

Подходы к описаниям (views) согласно ISO 42010:2022 могут быть двух
видов: прожекторные (projective) и синтетические (synthetic).

**Прожекторные** описания --- это как в театральном прожекторе, в
котором лампа белого цвета, но мы делаем цветной луч, просто
отфильтровывая все цвета кроме того, который нам понравится. По факту
это означает, что у нас есть большая база данных, в которой хранятся все
связанные между собой разные модели разных ролевых описаний --- все
вместе, соответствующие какой-то модели данных. Эта модель данных ---
общая онтология самых разных предметных областей. Когда нам нужны данные
одной модели (model), то просто из этой совместно хранящейся одной базы
данных как документа с системным описанием моделей системы для самых
разных мета-моделей, которые увязаны типами одной мета-мета-модели
отфильтровывается только то, что нужно в части мета-модели (запрошенные
ролевые описания, или даже запрошенные отдельные модели из этих
описаний) и отображается в подходящих форматах документов. Если мы
смотрим на какие-то отдельные классы компьютерного корпоративного софта
(ERP, CRM, PLM и прочие «трёхбуквенные аббревиатуры»), то внутри каждого
такого софта можно обнаружить базу данных, которая пытается воплощать в
себе прожекторное описание. Если хочется получить какое-то отдельное
описание с отдельными характеристиками системы, то надо просто выполнить
какой-то запрос на языке запросов к этой базе данных.

**Синтетические** описания --- это когда наоборот: исходные ролевые
описания даны в виде отдельных документов моделей, причём каждая модель
документирована не просто как часть одной общей для всех моделей базы
данных (как в прожекторных описаниях), а отдельный бумажный или
электронный документ в отдельной онтологии. Между этими автономными
моделями из отдельных документов по возможности устанавливаются
**правила соответствия** (correspondence rules, «этот объект этой
модели --- это вон тот элемент вон той модели»), и общая модель
системного описания тем самым получается синтетически, объединением
отдельных автономных видов моделей. Рассуждения про системные/полные и
ролевые/аспектные описания системы при этом не меняются от того, как
собираются эти описания из документации моделей --- сразу в общем
документе (прожекторный подход к описаниям) или после создания отдельных
документов моделей (синтетический подход). Нельзя сказать, какой метод
побеждает:

-   Прожекторный метод очень удобен: всё собрано в одном месте, да ещё и
    согласовано. Проблем типа «вот тут у меня длина в футах, а у вас в
    метрах, а вот тут у них в попугаях» не возникает, мета-моделирование
    централизовано!
-   Это кошмар для архитекторов: чтобы чуть-чуть пошевелить какое-то
    описание, надо шевелить сразу все описания вместе, поддерживать это
    согласование! Прожекторный метод становится «бутылочным горлышком»,
    запрещая по факту автономную работу команд, занимающихся разными
    описаниями.
-   Если у вас уже есть автономные моделеры, удобные для
    документирования каких-то отдельных описаний в рамках синтетического
    подхода, очень трудно заставить от них отказаться, чтобы перейти на
    новые моделеры, которые хранят свои модели в общей базе данных в
    рамках прожекторного подхода --- усилия по переучиванию людей и
    переналаживанию инструментария обычно считают не слишком
    оправданными, даже если постоянно сталкиваются с какими-то
    коллизиями между моделями. Конечно, количество коллизий заведомо
    больше при синтетическом подходе.

Синтетические и прожекторные описания оказываются эквивалентными в плане
мышления о работе с описаниями. В ISO 42010:2022 явно указывается, что
все основные идеи по работе с описаниями (например, требование указания
viewpoint для любого view) работает для обоих вариантов. Просто в
синтетических описаниях приходится много сил тратить на согласование
независимо подготовленных описаний, «интеграцию данных жизненного
цикла». А в прожекторных описаниях приходится много сил тратить ещё до
начала моделирования конкретной системы на то, чтобы согласовать методы
описания для документирования всех аспектных/частных описаний в одной
базе данных. В общем случае, конечно, побеждают синтетические описания,
поскольку они не подразумевают предварительной огромной работы по
интеграции инструментов моделирования. Но желание иметь прожекторные
описания, с которыми потом удобно работать, достаточно сильно. Поэтому
современные проекты имеют несколько видов прожекторных описаний, вместе
составляющих синтетическое (ибо ни один из видов прожекторных описаний
не отражает все проектные предметы интереса).

Как увязывают описания в каком-то большом проекте? Обычно используют
идеи из стандарта ISO 11354-1:2011, framework for enterprise
interoperability (он будет помянут в подразделе «Платформы и
инструментальные стеки» нашего курса, а затем в курсе «Системная
инженерия» в подразделе «Интеграция данных»):

-   Интеграция: есть общий метод описания, которому следуют все
    участники проекта, это прямая отсылка к прожекторному подходу. Все
    части проекта в момент создания согласовываются между собой. Дорого,
    долго, но гарантированно работает! Это вариант «в нашем проекте все
    говорят на окситанском
    языке^[[https://ru.wikipedia.org/wiki/Окситанский\_язык](https://ru.wikipedia.org/wiki/Окситанский_язык)],
    другие языки запрещены. Кто начинает у нас работать, должен выучить
    окситанский язык».
-   Унификация: согласовываются только описания, которыми обмениваются
    подсистемы (например, подразделения в организации или космический
    корабль с ускорительным блоком), а внутри каждой подсистемы описания
    более-менее автономны/инкапсулированы. Прожекторный подход в каждой
    подсистеме, далее объявленная публично модель взаимодействия --- и
    прожекторный подход в системе в целом. Это вариант «вы все говорите
    как хотите, хоть по-испански или по-английски, или вот тут у нас три
    китайца говорят на мандаринском, но рабочий язык у нас будет ---
    окситанский, совещания только на нём, словарь и учебник опубликованы
    в стандарте».
-   Федерирование: увы, в этой ситуации согласовать заранее ничего
    нельзя. Скажем, мы пытаемся согласовать описания, которыми
    обмениваются системы, разработчики которых ничего не знали друг о
    друге. Это будет соответствовать синтетическому подходу. В жизни это
    будет два варианта. Обычный: «вот тут надо наладить общение между
    китайцем и индийцем, давайте найдём мандаринско-хинди переводчика».
    Жизнь становится ужасной при этом варианте, начиная с буквально трёх
    общающихся: для них нужно будет найти трёх переводчиков, которые
    будут находить соответствия и переводить с одного языка на другой
    (да ещё часто это надо делать в обе стороны). После того, как эта
    проблема в проекте обнаружена, предлагается какой-то из этих языков
    сделать «нейтральным рабочим», например, английский (даже если на
    этом языке никто из участников проекта не говорит, но совещания
    теперь будут вестись на нём). Конечно, это попытка перейти от
    федерирования к унификации. При этом потребуется только переводчики
    с «рабочего английского» на язык каждого участника совещаний, но в
    больших проектах договориться о том, будет ли это «рабочий
    английский», «рабочий мандарин», «рабочий окситанский» --- это
    довольно трудно.

Отдельное замечание --- это мы говорим пока только об описаниях в
локальных представлениях. Описания в распределённых представлениях
(например, в виде больших языковых моделей в AI-агентах, или в виде
просто нейросетей, если речь идёт о каких-то простых описаниях
производственных процессов в непрерывном производстве, например,
химическом производстве или генерировании электроэнергии) тут мы не
рассматриваем. Но это не означает, что их нет и их можно не учитывать.
Если рассматривать эти описания, то они сделаны тоже каким-то методом
(например, методами глубокого
обучения^[<https://en.wikipedia.org/wiki/Deep_learning>]).
В этой области пока нет какого-то понимания методов работы с такими
описаниями, но она довольно бурно развивается. По большому счёту, работа
с описаниями в человеческой голове тоже проходит в распределённых
представлениях. Лучшая практика тут --- попробовать отмоделировать
нужные части этих описаний при помощи локальных представлений. Тут
работает ход, аналогичный вышеописанным ходам с интегрированием,
унификацией и федерированием: внутри каждого такого описания может быть
что угодно, но для коммуникации надо будет перейти к локальным
представлениям --- и тогда будет работать всё, что известно про
системные описания, данные в локальных/символьных представлениях.
