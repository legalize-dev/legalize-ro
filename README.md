# Legalize Romania 🇷🇴

Legislația României în format Markdown, cu control de versiuni prin Git.

Fiecare lege este un fișier, fiecare reformă este un commit.

## Structura

```
ro/
  RO-47355.md      ← Constituția României
  RO-798.md        ← Legea nr. 31/1990 (societăți comerciale)
  RO-171282.md     ← Codul Fiscal
  ...
```

## Frontmatter

Fiecare fișier conține un antet YAML cu metadate:

```yaml
---
title: "CONSTITUȚIE din 21 noiembrie 1991 (republicată)"
identifier: "RO-47355"
country: "ro"
rank: "constituție"
publication_date: "2003-10-31"
status: "in_force"
source: "https://legislatie.just.ro/Public/DetaliiDocument/47355"
department: "PARLAMENTUL"
---
```

## Sursă

Datele provin din [Portal Legislativ](https://legislatie.just.ro/), baza de date legislativă a Ministerului Justiției din România.

Textele legislative oficiale sunt de domeniu public conform art. 9 lit. b) din Legea nr. 8/1996 privind dreptul de autor.

## Legalize

Acest repository face parte din proiectul [Legalize](https://legalize.dev) — legislație accesibilă pentru toți.

## Licență

MIT — vezi [LICENSE](LICENSE).
