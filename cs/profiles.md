# Profiles

Profil = adresa / účet / platební údaje pro konkrétní shop. Bez správného profilu task nepojede spolehlivě.

## Vytvoření profilu

1. Otevři sekci **Profiles**
2. Klikni **New profile**
3. Vyber **stránku (site)**
4. Pojmenuj profil (libovolně), **nebo**
5. Je možnost si automaticky propsat profil z Generatoru — vygenerované účty se propíšou do Profiles a rovnou z nich uděláš ready profily

## Random údaje (CZ / SK)

U každého profilu můžeš doplnit náhodné údaje podle země:

- Do příslušného řádku napiš `cz` nebo `sk`
- Bot si údaje doplní sám

Hodí se na rychlé generování adresních dat. Pořád kontroluj, že adresa dává smysl pro daný shop (hlavně Rohlik).

## Tipy podle stránek

**CDMC:**

Jde o Shoptet → můžeš běžet **guest** (nemusíš mít účet vytvořený přímo pro CDMC).

- **Vždy** u každého profilu zvol **pickup point ID**
- Guest je pohodlný, ale u důležitých dropů je účet často stabilnější

**Alza:**

- **Doporučeno běhat s účty** — guest může bugovat / končit errorem
- Modul je primárně ready pro **Pokémon** produkty
- Nové účty si udělej v [Generatoru](generator.md) — propsou se do Profiles
- **Nezapomeň mít zaškrtnuté Alzaboxy**

**Toredo:**

Stejná logika jako u CDMC (Shoptet):

- Guest možný
- **Pickup point ID** vždy nastav
- Účet = lepší session handling

**Dobré knihy:**

- Dole můžeš zaškrtnout **pickup na prodejně**
- Guest jde, ale **raději běhej s účty** — lepší session handling, méně věcí co se může rozbít

**Rohlik:**

- **Silně doporučeno** mít hotové účty a doplnit je do profilu
- Rohlik je „random“ v produktech a adresách — některé regiony produkt nevidí in-stock, jiné ano
- Adresu vyplň **doslova přesně** (ulice, město, PSČ / ZIP) podle reálné adresy u účtu, ať nedostaneš zbytečný error

**Černý rytíř:**

- Účty si musíš **generovat / zakládat sám**
- Přidávají se **jen reálně existující účty** — guest checkout tady ne
- Je možnost **pickup na prodejně**
- **Nezapomeň vybrat pickup point**

**Shopify:**

- Vyplň **CC detaily** (platební karta) v profilu
- Bez správných platebních údajů checkout nedoběhne

Profily **exportuj** po nastavení — viz backup v [Stažení a spuštění](stazeni-bota.md).
