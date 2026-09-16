# Přispívání

Krátký postup pro lidi i boty. Cíl: doplnit **obrázky, schémata a ověřené podklady** — ne vymýšlet technická fakta o M9T.

## Obrázky (`assets/images/`)

- Pouze použitelné fotky z dílny (detail součásti, montáž, poškození).
- Dostatečné DPI / ostré; žádné watermarky ani silné komprese.
- Pojmenování: viz `assets/images/README.md`.
- Do PR uveďte zdroj (vlastní fotka / povolený zdroj) a k jaké kartě/sekci atlasu patří.

## Schémata (`assets/schemata/`)

- Preferujte SVG nebo PNG (zapojení, pinouty, hydraulika).
- Konvence pojmenování a typů: viz `assets/schemata/README.md`.
- U každého schématu uveďte, zda jde o odvozené / ověřené vůči TIS, nebo pracovní náčrt.

## Ověření před merge

1. Vyplňte položku v `verification/CHECKLIST.md` (nebo nový checklist podle šablony).
2. Ověřte proti **TIS / VIN** a odpovídající **kartě v atlasu**.
3. Neověřené materiály označte v PR jako `draft` / `needs-verification`.
4. Merge až po kontrole checklistu — žádné „asi správně“.

## Texty v `docs/`

- Doplňujte stuby v češtině, stručně.
- Nevymýšlejte hodnoty, limity ani postupy bez zdroje.
- Odkazujte na atlas a na soubory v `assets/`.

## Boti

- Stejná pravidla jako u lidí.
- Commit message: co přibylo + jestli je ověřeno (`verified` / `unverified`).
- Neměnit živý atlas přímo z tohoto repa — jen podklady.
