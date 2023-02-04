# Readme

https://alphabetizer.flap.tv/

[Non-empty checks](https://michaelcurrin.github.io/dev-cheatsheets/cheatsheets/jekyll/liquid/conditionals/non-empty.html)
[](http://shnurcki.narod.ru/poleznosti/toponim/krym/tsk_a.html)
[](http://geokrym.narod.ru/toponim/t-l-o.html)

http://eurotourist.club/viewtopic.php?f=83&t=119616&start=30
http://www.caucasia.ru/
http://rodnik-crimea.ru/Tds.html

```liquid
{{ content | remove: "<p>" | remove: "</p>"
    | replace: "[В]", "[В](# 'Восток')"
    | replace: "[З]", "[З](# 'Запад')"
    | replace: "[С]", "[С](# 'Север')"
    | replace: "[Ю]", "[Ю](# 'Юг')" }}
```

## Запросы терминал

`site/assets/toponyms/temp`
`awk '{print $0 > "out" NR ".md"}' RS='' in.yml`
`awk '{print $0 > "out" NR ".md"}' RS='\n⒵\n' in.yml`

`cat ./* > out.md`

`(---\ntitle: (.*)\ntags:.*\n)(synonyms:\n)`

`---\n---\n❮$2❯\n$1`

Термин топонимия означает совокупность топонимов географических названий
какой-либо местности, региона.

Топонимы подразделяются на:

- ойконимы - названия населенных пунктов,
- оронимы - названия гор и других форм рельефа,
- гидронимы - названия водных объектов.

- многокомпонентного ойконим: I., II., III., ...
  - ойконим толкуеся двояко: 1., 2., 3., ...
    - близкие по значению варианты: 1), 2), 3), ...
      - варианты толкований а), б), в), ...

`(Ⅰ|Ⅱ|Ⅲ|Ⅳ|Ⅴ|Ⅵ|Ⅶ|Ⅷ|Ⅸ|Ⅹ|Ⅺ|Ⅻ)` - составные компоненты
`(①|②|③|④|⑤|⑥|⑦|⑧|⑨)`
`(⒈|⒉|⒊|⒋|⒌|⒍|⒎|⒏|⒐|⒑|⒒|⒓)` - разные по значению варианты
`(⑴|⑵|⑶|⑷|⑸|⑹|⑺|⑻|⑼|⑽|⑾|⑿)` - близкие по значению варианты
`(⒜|⒝|⒞|⒟|⒠|⒡|⒢|⒣|⒤|⒥|⒦|⒧|⒨|⒩|⒪|⒫|⒬|⒭|⒮|⒯|⒰|⒱|⒲|⒳|⒴|⒵)` - варианты толкований

`⦃⦄`

### Населенные пункты

< - При наличии нескольких исторических названий у  одного населённого пункта,
все они перечисляются через знак (<) в обратном хоронологическом порядке.

→ - Если н.п. вошёл в состав другого.

 - В случаях, когда названия населённых пунктов поддаются толкованию, словарная
статья состоит из двух частей: левой, где находится ойконим, который может иметь
несколько вариантов, и правой, отделённой значком (), где истолковывается это
название. Толкуемые слова (и  компоненты слов) вписываются в правую часть:

### Сокращения

`⦅$1.⦆`

`(см|ср|араб|греч|диал|др|иран|итал|латин|монг|тюрк|черкесск)\.`
`(дртюрк|кртат|срв)`

см. ⦅см.⦆ смотри
ср. ⦅ср.⦆ сравни

греч. ⦅греч.⦆ греческий язык
диал. ⦅диал.⦆ диалект
др. ⦅др.⦆ древний
дртюрк ⦅дртюрк⦆ древнетюркский язы
иран. ⦅иран.⦆ ираноязычный
итал. ⦅итал.⦆ итальянский язык
кртат ⦅кртат.⦆ крымскотатарский язык
латин. ⦅латин.⦆ латинский язык 
монг. ⦅монг.⦆ монгольский, монголоязычны
срв ⦅срв.⦆ средневековый
тюрк. ⦅тюрк.⦆ тюркские языки
черкесск. ⦅черкесск.⦆ черкесский

`(РПН|ИЛ)`

РПН ⦅рпн.⦆ родоплеменное название
ИЛ ⦅ил.⦆ имя личное
ⓩЮБК Южный берег Крыма 
Заповедник.  Крымское государственное  заповедно-охотничье хозяйство в центральной части горного Крыма

`(б|букв|возм)\.`

ⓩб. бывший
ⓩбукв. буквально
ⓩвозм. возможно

м.

ⓩбасс. бассейн 
ⓩвдп водопад 
ⓩвдрз водораздел 
ⓩвдхр водохранилище 
ⓩвозв. возвышенность 
ⓩвпад. впадает 
ⓩг. гора 
ⓩдол. долина 
ⓩист. исток 
ⓩм. мыс 
ⓩмасс. массив 
ⓩмн. ч. множественное число 
ⓩназ. называется 
ⓩназв. название 
ⓩнач. начинается 
ⓩнп населенный пунк 
ⓩов. овраг 
ⓩоз. озеро 
ⓩоконеч. оконечность 
ⓩпер. перевал 
ⓩпещ. пещера, пещерный 
ⓩп-ов полуостров 
ⓩпр. приток 
ⓩпос. поселок 
ⓩпрох. горный проход 
ⓩр. река 
ⓩтеч. течение 
ⓩущ. ущелье 
ⓩхр. хребет 

`(верх|сред|ниж|л|п)\.`

ⓩверх. верховье(я); верхний
ⓩсред. средний
ⓩниж. нижний
ⓩл. левый
ⓩп. правый

ⓩВ восток 
ⓩЗ запад 
ⓩС север 
ⓩЮ юг 

`(вост|зап|с-вост|с-зап|сев|ю-вост|ю-зап|юж)\.`

ⓩвост. восточный
ⓩзап. западный
ⓩс-вост. северо-восточный
ⓩс-зап. северо-западный
ⓩсев. северный
ⓩю-вост. юго-восточный
ⓩю-зап. юго-западный
ⓩюж. южный

`\((Кгв|Киров|Крпер|Ленин|Нижн|Разд|Севаст|Алушт|Бахч|Белог|Симф|Судак|Феодос|Черном|Ялт)\.\)`
(Кгв.) Красногвардейский район
(Киров.) Кировский район
(Крпер.) Красноперекопский район
(Ленин.) Ленинский район
(Нижн.) Нижнегорский район
(Разд.) Раздольненский район
(Севаст.) Севастопольский горсовет
(Алушт.) Алуштинский горсовет
(Бахч.) Бахчисарайский район
(Белог.) Белогорский район
(Судак.) Судакский район
(Феодос.) Феодосийский горсовет
(Черном.) Черноморский район
(Ялт.) Ялтинский горсовет

### Замены

`• Словарь ойконимов Крыма • [0-9]{3}`
`[0-9]{3} • Топонимика Крыма ::: 2010 ::: •`

`` -> ``
`[а-я][А-Я]`

`` -> 🛈

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

Counter:

а:

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

Специальные термины и понятия, встречающиеся в словаре

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

{% if page.names %}

{% capture title %}
{{ page.names | map: "name" | join: ", " }}

{% include links/toponyms/terms.md %}
{% endcapture %}
{% endif %}

{% assign title = "" %}
{% for item in page.names %}
{% capture title %}{{ item.name }}[^{{ item.footnote }}]{% endcapture %}
{{ title | append: item.name | append: "[^" | append: item.footnote | append: "], " }}
{% endfor %}

{% if page.title %}
{% capture title %}
{{ page.titles | map: "name" | join: ", " }}

{% include links/toponyms/terms.md %}
{% endcapture %}
{% endif %}

{{ content | remove: "<p>" | remove: "</p>"
    | replace: "[В]", "[В](# 'Восток'){:target='_blank'}"
    | replace: "[З]", "[З](# 'Запад'){:target='_blank'}"
    | replace: "[С]", "[С](# 'Север'){:target='_blank'}"
    | replace: "[Ю]", "[Ю](# 'Юг'){:target='_blank'}" }}