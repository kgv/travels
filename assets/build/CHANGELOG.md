# Changelog

- 1.0.1: `^- ([А-Я]) -`, `^(?!separator)`
- 1.0.2: `(см|ср)\.`
- 1.0.3: `([А-ЯЁ]+)\*` -> `⟦$1⟧`
- 1.0.4: `(см|ср)` -> ``
- 1.0.5: `“` -> `«`, `”` -> `»`
- 1.0.6: `\(\?\)` -> `❓`, `` -> ``, `([СЮЗВ]{1,3})–([СЮЗВ]{1,3})` -> `$1→$2`
- 1.0.7: `XVI` -> `①`
- 1.0.8: `1, 2, 3)` -> `⦃$1⦄, ⦃$2⦄, ⦃$3⦄`
- 1.0.9: `г.`, `гг.`, `p.`, `впад.`, `назв.` дол.  -> ``, `\.\.` -> `.®`
- 1.0.10: `⦃1⦄` -> `❶`
- 1.0.11: `Ж–7` -> `⦃Ж7⦄`
- 1.0.12: `⦅П.⦆\S`, `\(⦅см.⦆\)`, `рр.`, `басс`, `масс`, `вдрз`, `ЮЗ` -> ``
- 1.0.9: `` -> ``

`⦅(Алушт|Бахч|Белог|Кгв|Киров|Крпер|Ленин|Нижн|Разд|Севаст|Судак|Феодос|Черном|Ялт|Симф)\.⦆`

name: [^\]]*[②③④⑤⑥⑦⑧]\], content: 
]$\nname: \[[^\]]+[②③④⑤⑥⑦⑧]\], content: 
\]$\n[^:]+[②③④⑤⑥⑦⑧]: \[

homophones
Кара-Голь ②, ⟦Ай⟧-Валык ②

\[\{ synonyms:([^{]*\{ synonyms:){2}

names: (⟦?[А-Яа-яё]+⟧?-?)+ ?[①②③④⑤⑥⑦⑧]? [-–] [а-я(]
names: (⟦?[А-Я][а-яё]+⟧?-?)+ ?[①②③④⑤⑥⑦⑧] – [а-я]
names: (⟦?[А-Яа-я]+⟧? )+– [а-я]
[А-ЯЁ]–[0-9]{1,3}

ЮБК. м.

- 0.0.5: `([СЮЗВ]{1,3})–([СЮЗВ]{1,3})` -> `$1→$2`
- 0.0.6: `\(\?\)` -> `❓`
- 0.0.7: 
