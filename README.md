# Catalog Studio — program a aktualizácie

Hotový program **Catalog Studio** pre Windows: z tabuľky so skladovými alebo produktovými dátami (Excel, OpenDocument, CSV) vytvorí katalóg alebo cenník v Exceli, PDF a ako webovú stránku.

## Inštalácia

1. Stiahnite obsah repozitára: **Code › Download ZIP** a rozbaľte ho, napríklad do `C:\Programy\Catalog Studio`.
2. Program potrebuje **.NET 8 Desktop Runtime (x64)**: <https://dotnet.microsoft.com/download/dotnet/8.0>
3. Spustite `CatalogStudio.exe`. Nastavenia, šablóny a licencia sa ukladajú do priečinka `DATA` vedľa programu.

## Aktualizácia

V programe **O programe › Aktualizácie › Skontrolovať aktualizácie** — program stiahne novú verziu z tohto repozitára a reštartuje sa; nastavenia, šablóny a licencia ostanú.

- Aktualizácia v programe vymení súbor `CatalogStudio.exe`. Nové preklady získate, keď z tohto repozitára stiahnete aj priečinok `Languages`.

## Licencia

Bez licenčného kľúča je Catalog Studio **bezplatná verzia** a vytvára katalógy v Exceli. **PDF, webový katalóg a obrázky strán** sú v plnej verzii.

Licenčný kľúč si vyžiadate v programe: **O programe › Licencia. Kľúč patrí jednému počítaču a neexpiruje.

## Obsah

| Súbor / priečinok | |
|---|---|
| `CatalogStudio.exe` | program |
| `Languages` | preklady (slovenčina, angličtina, nemčina) |
| `LatoFont` | písmo Lato — SIL Open Font License (`OFL.txt`) |
| `Resources` | logo |
| `version.json` | posledná verzia pre kontrolu aktualizácií |

---

**English** — ready-to-run Catalog Studio for Windows (needs the .NET 8 Desktop Runtime, x64): download the ZIP and run `CatalogStudio.exe`. About › Updates installs new versions from this repository (versions 2.0.0 and 2.0.1: set the update source to the address above once). Without a license key the program creates Excel catalogs; PDF, the web catalog and page images need a key — request it under About › License (roman@magoc.sk).
