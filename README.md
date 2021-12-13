# Readme

https://alphabetizer.flap.tv/

[Non-empty checks](https://michaelcurrin.github.io/dev-cheatsheets/cheatsheets/jekyll/liquid/conditionals/non-empty.html)
[](http://shnurcki.narod.ru/poleznosti/toponim/krym/tsk_a.html)
[](http://geokrym.narod.ru/toponim/t-l-o.html)

http://eurotourist.club/viewtopic.php?f=83&t=119616&start=30
http://www.caucasia.ru/
http://rodnik-crimea.ru/Tds.html

awk '{print $0 > "out" NR ".md"}' RS='' in.md

2018:
1953 ^([^—]+)— $1--
65?

Термин топонимия означает совокупность топонимов географических названий
какой-либо местности, региона (следует отличать от топонимики - науки, изучающей
эти названия (топонимы).

Топонимы подразделяются на

- ойконимы - названия населенных пунктов,
- оронимы - названия гор и других форм рельефа,
- гидронимы - названия водных объектов.

< - При наличии нескольких исторических названий у  одного населённого пункта,
все они перечисляются через знак (<) в обратном хоронологическом порядке.

→ - Если н.п. вошёл в состав другого.

 - В случаях, когда названия населённых пунктов поддаются толкованию, словарная
статья состоит из двух частей: левой, где находится ойконим, который может иметь
несколько вариантов, и правой, отделённой значком (), где истолковывается это
название. Толкуемые слова (и  компоненты слов) вписываются в правую часть:

`• Словарь ойконимов Крыма • [0-9]{3}`
`[0-9]{3} • Топонимика Крыма ::: 2010 ::: •`

`` -> ``
`[а-я][А-Я]`

`` ->
🛈

`"` -> `→`

`“` -> `«`
`”` -> `»`
`«[^»]*$`

`«[^»]*«`, `»[^«]*»`
`(\S)«` -> `$1 «`

` \n` -> ` `

`^[А-Я]$` -> `---`

`^(.*)\n(ИЛМ|ИЛЖ|КСИ|РПН)` -> `$1 $2`

`  ` -> ` `
`\s+\n` -> `\n`
`-  ` -> `- `


`(\+\s*)\n(.*)`
`(<\s*)\n(.*)`
`(→)\n(.*)`
`(см\.\s*)\n(.*)`
`(,\s+)\n(.*)`
`(;\s+)\n(.*)`
-> `$1 $2`

`^(.)(.*)\n(?!\1)` -> `$1$2 `

`(\S)→`
`→(\S)`

\S→\S

`🛈.*🛈`
`(Перекопский уезд`
`l)`
`аль –`

(.*)\n(?!.*—)

\((?:(?:Алушт\.)|(?:Бахч\.)|(?:Белог\.)|(?:Джанк\.)|(?:Евпат\.)|(?:Керч\.)|(?:Кир\.)|(?:Кргв\.)|(?:Крпер\.)|(?:Ленинск\.)|(?:Нижн\.)|(?:Перв\.)|(?:Разд\.)|(?:Сак\.)|(?:Севас\.)|(?:Симф\.)|(?:Совет\.)|(?:Судак\.)|(?:Феод\.)|(?:Черн\.)|(?:Ялт\.))\).*\((?:(?:Алушт\.)|(?:Бахч\.)|(?:Белог\.)|(?:Джанк\.)|(?:Евпат\.)|(?:Керч\.)|(?:Кир\.)|(?:Кргв\.)|(?:Крпер\.)|(?:Ленинск\.)|(?:Нижн\.)|(?:Перв\.)|(?:Разд\.)|(?:Сак\.)|(?:Севас\.)|(?:Симф\.)|(?:Совет\.)|(?:Судак\.)|(?:Феод\.)|(?:Черн\.)|(?:Ялт\.))\)

\(((?:Алушт)|(?:Бахч)|(?:Белог)|(?:Джанк)|(?:Евпат)|(?:Керч)|(?:Кир)|(?:Кргв)|(?:Крпер)|(?:Ленинск)|(?:Нижн)|(?:Перв)|(?:Разд)|(?:Сак)|(?:Севас)|(?:Симф)|(?:Совет)|(?:Судак)|(?:Феод)|(?:Черн)|(?:Ялт))\)

«..., ...»

(ИЛМ|ИЛЖ|КСИ|РПН)\s$

? `(,)\n(.*)`
? `Алупка (Ялт.)`
? `Воинка (Крпер.)`
тарыРПН, кушРПН, КомЗЕТ, черкезРПН

Ком-ЗЕТ

БулганакВер-Борюс

Нижний Старая Новый

`\s+(#SIGN-.)\s+` -> `\n$1\n`

^(?![^(]*\()

---\n---\n(★.*)$

`🛈:(.*)(II.*)` -> `🛈:$1
  - $2`

`^  -(.*)3\.(.*)$` ->
```
  -$1
    - $2
```

`- - 1. ` -> `- - `

`^  - - (.*)2\.(.*)$` ->
```
  - - $1
    - $2
```

`^  ( |-) -(.*)4\)(.*)$` ->
```
  - - $1
    - $2
```

`^(  ( |-)*)` -> `$1 -`

`^(  ( |-)*.*)4\)(.*)$` ->
```
$1
      - - $3
```

🛈:
  - многокомпонентного ойконима (I., II., III.)
  - - ойконим толкуеся двояко (1., 2., 3. )
  - - - близкие по значению варианты (1), 2), 3))
  - - - - варианты толкований (а), б), в))
а:

Counter:


- 163(43+0): 43
- 164(41+0): 84
- 165(53+0): 137
- 166(50+0): 187
- 167(57+0): 244
- 168(53+0): 297
- 169(54+0): 351
- 170(60+0): 411
- 171(45+0): 456
- 172(45+0): 501
- 173(27+21): 549
- 174(15+0): 564

б:

- 174(10+27) 37
- 175(22+23) 82
- 176(24+31) 137
- 177(25+30) 192
- 178(34+23) 249
- 179(29+27) 305
- 180(26+23) 354
- 181(21+20) 395
- 182(22+36) 453
- 183(25+23) 501
- 184(26+30) 557
- 185(31+27) 615
- 186(36+10) 661

в:

- 186(23)
- 187(25+21) 69
- 188(24+34) 127
- 189(38+37) 202

г:

- 190(34+30) 64
- 191(37+32) 133
- 192(3) 136

д:

- 193()
- 194()
- 195()
- 196()
- 197()
- 198()
- 199()

Table:

`^(\|[^|]*\|)$`

`^(\|([^|]+\|){3})$`

\(((?:Алушт)|(?:Бахч)|(?:Белог)|(?:Джанк)|(?:Евпат)|(?:Керч)|(?:Кир)|(?:Кргв)|(?:Крпер)|(?:Ленинск)|(?:Нижн)|(?:Перв)|(?:Разд)|(?:Сак)|(?:Севас)|(?:Симф)|(?:Совет)|(?:Судак)|(?:Феод)|(?:Черн)|(?:Ялт))\)

\(((?:Алушт\.)|(?:Бахч\.)|(?:Белог\.)|(?:Джанк\.)|(?:Евпат\.)|(?:Керч\.)|(?:Кир\.)|(?:Кргв\.)|(?:Крпер\.)|(?:Ленинск\.)|(?:Нижн\.)|(?:Перв\.)|(?:Разд\.)|(?:Сак\.)|(?:Севас\.)|(?:Симф\.)|(?:Совет\.)|(?:Судак\.)|(?:Феод\.)|(?:Черн\.)|(?:Ялт\.)|(?:Арм\.)|(?:Севаст\.)|(?:Евпаторийский уезд)|(?:Перекопский уезд)|(?:Ялтинский уезд)|(?:Симферопольский уезд)|(?:Владиславовская волость)|(?:ЮБК))\)

`^\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|([^|]+)\|$`

- $1
- $2
- $3
- $4
- $5
- $6
- $7
- $8
- $9
- $10
- $11

^([^—]*)—(.*)$

^(⒈|⒉|⒊|⒋|⒌|⒍|⒎|⒏|⒐)\sср\.

Ⅰ|Ⅱ|Ⅲ|Ⅳ|Ⅴ|Ⅵ|Ⅶ|Ⅷ|Ⅸ|Ⅹ|Ⅺ|Ⅻ - составные компоненты
⒈|⒉|⒊|⒋|⒌|⒍|⒎|⒏|⒐|⒑|⒒|⒓ - группировка разных по значению вариантов
⑴|⑵|⑶|⑷|⑸|⑹|⑺|⑻|⑼|⑽|⑾|⑿ - группировка близких по значению вариантов
⒜|⒝|⒞|⒟|⒠|⒡|⒢|⒣|⒤|⒥|⒦|⒧|⒨|⒩|⒪|⒫|⒬|⒭|⒮|⒯|⒰|⒱|⒲|⒳|⒴|⒵ - 

Мои правки:
- келечи ≈
- кесек а)

`^(⒈|⒉|⒊|⒋|⒌|⒍|⒎|⒏|⒐)(.*?)\sа\)` -> `$1$2\n⒜`
`^(⒜)(.*?)\sб\)` -> `$1$2\n⒝`

`^  (⒜|⒝|⒞|⒟|⒠|⒡|⒢|⒣|⒤|⒥)`

`\[=[^\]]+\]`
---\ntitle.*\n---\n[^0-9].*\n
тюрк

---

`[0-9]{1,3}(\s+фото)?$`

`[^\n]\n\S`
`[А-Я]–[0-9]{1,3}`
`\[¹([А-Я]–[0-9]{1,3})\]`
`\[¹([А-Я][0-9]{1,3})\]`

[А-Я],\s+[А-Я]–[0-9]{1,3},\s+[0-9]{1,3}
([А-Я]),\s+([А-Я])–([0-9]{1,3}),\s+([0-9]{1,3})

\[&([А-Я])-[0-9]{1,3}\][^. ,–] -

([А-Я]),([А-Я])–[0-9]{1,3}[0-9]{1,3}
[А-Я], \[\$[А-Я][0-9]{1,3}\]

((С|Ю|З|В){1,3})–((С|Ю|З|В){1,3})
((С|Ю|З|В){1,3})-((С|Ю|З|В){1,3})

- минус
‐ дефис
﹣ Среднее тире
— Длинное тире

^[^А-Я]
с – м.
[%тюз]
Высота Феодосийская
(?)

`\[@[^\]]+\]`

^.+, #.*$

^\[%[^\]]+\]

([А-Я][а-я]*)\*

^(\[%[^\]]+\])-(\[%[^\]]+\])-([А-ЯЁ][а-яё]+)\*

^([А-Я][а-я]*)-([А-Я][а-я]*)\*

([^\s]+)\*

^(((([А-ЯЁ][а-яё]+)|(\[%[^\]]+\]))-?){1,4})\s*((I|V)*)

①\s*–

①[^–]
301:

\|.*?\|.*?\| [А-ЯЁ][а-яё]+(-[А-ЯЁ][а-яё]+)*(\s*,?\s*[А-ЯЁ][а-яё]+(-[А-ЯЁ][а-яё]+)*)*
^(\|.*?)\|.*?\| ([А-ЯЁ][а-яё]+(-[А-ЯЁ][а-яё]+)*(\s*,?\s*[А-ЯЁ][а-яё]+(-[А-ЯЁ][а-яё]+)*)*)

((балка)|(башня)|(бугор)|(бухта)|(водопад)|(гора)|(горы)|(грот)|(долина)|(залив)|(источник)|(камни)|(каньон)|(колодец)|(коса)|(курган)|(море)|(мыс)|(озеро)|(оползень)|(перевал)|(перешеек)|(пещера)|(полуостров)|(поляна)|(река)|(речка)|(ручей)|(седло)|(скала)|(скалы)|(стрелка)|(тропа)|(увал)|(утес)|(ущелье)|(фонтан)|(холм)|(хребет)|(шахта)|(шоссе)|(яйла))

балка
башня
бугор
бухта
водопад
гора
горы
грот
долина
залив
источник
камни
каньон
колодец
коса
курган
море
мыс
озеро
оползень
перевал
перешеек
пещера
полуостров
поляна
река
речка
ручей
седло
скала
скалы
стрелка
тропа
увал
утес
ущелье
фонтан
холм
хребет
шахта
шоссе
яйла

((тропа)|(скала)|(гора)|(амфитеатр)|(балка)|(бровка)|(вершина)|(водораздел)|(воронки)|(карстовые воронки)|(гребень)|(горный гребень)|(массив)|(горный массив)|(проход)|(горный проход)|(хребет)|(горный хребет)|(грот)|(городище)|(гряды)|(долины)|(каньон)|(коса)|(котловина)|(кулуар)|(куэсты)|(лощина)|(мыс)|(нагорье)|(овраги)|(останцы)|(отторженцы)|(перевал)|(пещеры-источники)|(пещеры-поноры)|(плато)|(понор)|(расселина)|(седловина)|(столовые горы)|(стоянка)|(стрелка)|(урочище)|(ущелье)|(утес)|(холмы)|(шахта))

скала
гора
амфитеатр
балка
бровка
вершина
водораздел
воронки
карстовые воронки
гребень
горный гребень
массив
горный массив
проход
горный проход
хребет
горный хребет
грот
городище
гряды
долины
каньон
коса
котловина
кулуар
куэсты
лощина
мыс
нагорье
овраги
останцы
отторженцы
перевал
пещеры-источники
пещеры-поноры
плато
понор
расселина
седловина
столовые горы
стоянка
стрелка
урочище
ущелье
утес
холмы
шахта

Малый
Большой
Западный
Верхний
Нижний

Амфитеатр – полукруглое замыкание склонов; в Крыму обычно встречается в верховьях ущелий, долин.
Балка – небольшая эрозионная долина, сухая или с временным водотоком; пологие ее склоны задернованы или покрыты рыхлыми отложениями. В Крыму балками часто называют неглубокие ущелья или облесенные овраги: границы между этими понятиями здесь в известной мере стерты.
Бровка – резкий перелом склона, отделяющий вышележащую пологую его часть или горизонтальную поверхность от расположенного ниже более крутого участка.
Вершина – высшая точка или самая высокая часть какого-либо поднятия (холма, горы, горного массива или хребта), откуда местность понижается во все стороны.
Водораздел – линия, разделяющая смежные бассейны (водосборы) рек, водоемов.
Воронки – см. карстовые воронки.
Карстовые воронки – замкнутые впадины чашеобразной, конической или неправильной формы, часто с понором на дне; широко распространенные формы карста.
Гребень – см. горный гребень.
Горный гребень – наиболее высокая часть горного хребта или массива; обычно резко выделяется на фоне неба. Может иметь различные формы: зубчатую, округлую, платообразную.
Массив – см. горный массив.
Горный массив – более или менее изолированный участок гор, имеющий примерно одинаковую длину и ширину и часто отличающийся относительно слабой расчлененностью.
Проход – см. горный проход.
Горный проход – сквозное глубокое понижение в горном хребте, реже между близко расположенными хребтами. В Крыму часто отожествляются с перевалами, через которые проходят тропы или грунтовые дороги.
Хребет – см. горный хребет.
Горный хребет – линейно вытянутое горное поднятие со склонами, обращенными в противоположные стороны.
Грот – 1. неглубокая пещера со сводчатым потолком и широким входом; 2. значительно расширенная, с высоким сводом часть пещеры после узкого прохода.
Городище – см. “пещерные города”.
Гряды – общее название для вытянутых возвышенностей различного размера, высоты, происхождения.
Долины – удлиненные широкие впадины вдоль речного русла, среди гор; имеют однообразное падение по тальвегу.
Каньон – глубокая речная долина с очень крутым, нередко отвесным или ступенчатым склоном и узким дном, часто полностью занятым руслом реки.
Коса – низкая намывная полоса суши на берегу моря, озера, причлененная к берегу и вдающаяся клином в акваторию.
Котловина – отрицательная форма рельефа, округлая или слабо вытянутая в плане.
Кулуар – ложбина на крутом, лишенном растительности склоне горы, по которой скатываются камни или лавины.
Куэсты – возвышенные гряды с асимметричными склонами (в Крыму обычно южный крутой, северный пологий).
Лощина – долина с мягкими очертаниями и пологими задернованными склонами.
Мыс – участок суши, вдающийся в море, озеро или реку.
Нагорье – обширное горное поднятие, представляющее собой сочетание плато с отдельными вершинами и хребтами; ср. яйла.
Овраги – отрицательные эрозионные формы рельефа с крутыми склонами, сильно разветвленные; образование их связано с деятельностью временных (иногда постоянных) водотоков.
Останцы – изолированные возвышенности, сохранившиеся от разрушения участки существовавшей некогда более высокой поверхности.
Отторженцы – изолированно стоящие горы и скалы, которые в результате тектонических процессов отделились от места своего коренного залегания и сместились по склону.
Перевал – понижение в гребне горного хребта или массива, доступное для его пересечения, обычно с удобными подходами“пещерные города”, городища средневековые укрепленные поселения, которые частично располагались в искусственных и естественных пещерах Второй гряды крымских гор.
Пещеры-источники – подземные полости, из которых постоянно или периодически изливалась вода нижних ярусов водоносных систем.
Пещеры-поноры – пещеры-поглотители, собиравшие воду со своих поверхностных водосборов.
Плато – возвышенная плоская или волнистая равнина, расположенная примерно на одном уровне и отделенная отчетливыми склонами от находящейся ниже равнины.
Понор – естественное отверстие на поверхности закарстованного массива, поглощающее и отводящее в глубину дождевую, талую и речную воду.
Расселина – открытая трещина в скальных породах.
Седловина – неглубокая перевальная выемка с пологими подъемами к соседним высотам скала, – утес, выдающаяся оконечность горного отрога или одиноко стоящая каменная глыба, сложенная устойчивыми к выветриванию горными породами.
Столовые горы – горы с плоскими вершинами и более или менее крутыми, иногда ступенчатыми склонами.
?Стоянка – временный лагерь древних охотников, рыболовов, скотоводов.
Стрелка – узкий и длинный полуостров, коса, перемычка.
Урочище – участок местности, отличный от окружающих какими-либо естественными признаками: поляна или болото среди леса, роща среди поля и т.д.
Утес – см. скала.
Ущелье – узкая и глубокая, с крутыми склонами горная долина, выработанная рекой в твердых коренных породах; глубина обычно превосходит ширину; в сечении образуется острый угол.
Холмы – небольшие возвышенности различных очертаний с мягкими контурами склонов и относительной высотой не более 200 м.
Шахта – вертикальная карстовая полость глубиной свыше 20 м. Шахта с большим диаметром называется пропастью.

Исполиновы котлы – см. эврозионные котлы.
Эврозионные котлы, – исполиновы котлы круглые углубления, которые вырабатываются в скалистом ложе и бортах реки водоворотами, падающей или стремительно бегущей воды.

Яйла – волнистое, почти безлесное плато, вершинная поверхность Главной гряды Крымских гор, преимущественно на южных и юго-западных ее участках.

“Фонтан” – в Крыму название каптированных источников, в которых вода течет из трубы в каменной стенке; ниже обычно бассейн или каменное корыто. То же, что тюрк. чешме.

[*басс*] бассейн
[*бывш*] бывший
[*вдпд*] водопад
[*вдрз*] водораздел
[*вдхр*] водохранилище
[*верх*] верховье(я), верхний

[@ороним@]

((балка)|(бугор)|(вершина)|(высота)|(высоты)|(воронка)|(гора)|(горы)|(гребень)|(грот)|(гряда)|(долина)|(камень)|(камни)|(каньон)|(колодец)|(коса)|(котловина)|(кулуар)|(курган)|(куэста)|(лощина)|(массив)|(мыс)|(нагорье)|(овраг)|(оползень)|(останец)|(отторженец)|(перевал)|(перешеек)|(пещера)|(плато)|(поляна)|(проход)|(расселина)|(седло)|(седловина)|(скала)|(скалы)|(стрелка)|(увал)|(урочище)|(утес)|(ущелье)|(холм)|(хребет)|(хребет)|(шахта)|(яйла))

- балка
- бугор
- вершина
- высота
- высоты
- воронка
- гора
- горы
- гребень
- грот
- гряда
- долина
- камень
- камни
- каньон
- ? колодец
- коса
- котловина
- кулуар
- курган
- куэста
- лощина
- массив
- мыс
- нагорье
- овраг
- оползень
- останец
- отторженец
- перевал
- перешеек
- пещера
- плато
- поляна
- проход
- расселина
- седло
- седловина
- скала
- скалы
- стрелка
- увал
- урочище
- утес
- ущелье
- холм
- хребет
- хребет
- шахта
- яйла

  спелеоним

(\[#((грот)|(колодец)|(лабиринт)|(пещера)|(пропасть)|(шахта))#\])

- грот
- колодец
- лабиринт
- пещера
- пропасть
- шахта

[@гидроним@]

(\[#((бухта)|(водопад)|(залив)|(источник)|(море)|(озеро)|(река)|(речка)|(ручей)|(фонтан))#\])

- бухта
- водопад
- залив
- источник
- море
- озеро
- река
- речка
- ручей
- фонтан

ойконим

[@дромоним@]

- тропа
- шоссе

[@инсулоним@]

- остров
- полуостров

^(\|[^|]*\[%узень%\].*?\|).*
^\|[^|]+\|[^|]+\|\s+\|.*$
^\|[^|]+\|\s+\|.*$
^\|[^|]+\| . (?!\[@гидроним@\] \[@ороним@\])[^|]+\|[^|]+\|.*балка

высоты
горы
камни
речка
скалы

\[%([^%]+)%\]

^\|\s*([^|]*?)\s*\|\s*([^|]*?)\s*\|\s*([^|]*?)\s*\|\s*([^|]*?)\s*\|\s*([^|]*?)\s*\|
---
title: $1
tags: $2
synonyms: $3
temp: "$5"
---
$4

```
{% if post.id %}
  {% assign title = post.title | markdownify | remove: "<p>" | remove: "</p>" %}
{% else %}
  {% assign title = post.title %}
{% endif %}
```
