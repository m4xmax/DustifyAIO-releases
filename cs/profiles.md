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
- Po úspěšném checkoutu se vygeneruje **payment link** — najdeš ho v botovi nebo ve webhooku
- Je potřeba **ASAP zaplatit**, ale měl by tam být chvilkový hold

**Alza:**

- **Doporučeno běhat s účty** — guest může bugovat / končit errorem
- Modul je primárně ready pro **Pokémon** produkty
- Nové účty si udělej v [Generatoru](generator.md) — propsou se do Profiles
- **Nezapomeň mít zaškrtnuté Alzaboxy**
- Platba je **až po vyzvednutí z Alzaboxu**

**Toredo:**

Stejná logika jako u CDMC (Shoptet):

- Guest možný
- **Pickup point ID** vždy nastav
- Účet = lepší session handling
- Po checkoutu se vygeneruje **payment link** v botovi nebo ve webhooku
- Pokud o objednávku stojíš, je potřeba ho **zaplatit**

**Dobré knihy:**

- Dole můžeš zaškrtnout **pickup na prodejně**
- Guest jde, ale **raději běhej s účty** — lepší session handling, méně věcí co se může rozbít
- Buď pickup na prodejně, **nebo** se generuje **payment link**, který je potřeba **ASAP zaplatit**

**Rohlik:**

- **Silně doporučeno** mít hotové účty a doplnit je do profilu
- Rohlik je „random“ v produktech a adresách — některé regiony produkt nevidí in-stock, jiné ano
- Adresu vyplň **doslova přesně** (ulice, město, PSČ / ZIP) podle reálné adresy u účtu, ať nedostaneš zbytečný error
- Platba je **po doručení na adresu**
- Čas doručení se bere ze **standardní nabídky**, která je pro tvoji adresu nastavená právě v době checkoutu

**Černý rytíř:**

- Účty si musíš **generovat / zakládat sám**
- Přidávají se **jen reálně existující účty** — guest checkout tady ne
- Je možnost **pickup na prodejně**
- **Nezapomeň vybrat pickup point**
- Generuje se **payment link**, který tě po kliknutí hned hodí do platby — znovu je potřeba **ASAP zaplatit**
- Alternativa: **pickup**

**Shopify:**

- **Jediný modul**, kde je potřeba vyplnit **card details** (platební karta) v profilu
- Bez správných platebních údajů checkout nedoběhne
- Pro **test checkouty** klidně kartu freezni, nebo neměj dostatečný balance na účtu

Profily **exportuj** po nastavení — viz backup v [Stažení a spuštění](stazeni-bota.md).
