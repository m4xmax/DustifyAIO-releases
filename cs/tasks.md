# Tasks

Task = jedna běžící session (monitor / checkout) napojená na site, profil a volitelně proxy group.

## Vytvoření tasků

1. Otevři **Tasks**
2. Klikni **Create tasks**
3. Přidej jednotlivé tasky nebo **task groups**
4. Tasky si můžeš libovolně **přejmenovávat**
5. Klidně si vytvoř **více tasků pro stejný site** (různé produkty, profily, delaye)

## Nastavení

U tasků můžeš nastavit mimo jiné:

- **Custom monitor delay**
- **Error delay**
- Site / product
- Profile
- Proxy group

Delaye si přizpůsob podle shopu a proxy kvality. Když nevíš, začni s defaulty a upravuj až podle behaviouru.

## Proxies u tasků

Proxy group vybíráš přímo u tasku (skupiny vytváříš v [Proxies](proxies.md)).

- **Alza:** doporučeno běhat na proxies, ale není to nutnost
- U chráněnějších shopů (např. Shopify / CF) mají dobré proxies větší vliv na success rate

## STOP ALL (panic button)

**STOP ALL** okamžitě zastaví **všechny** běžící tasky.

Použij když:

- něco jede blbě napříč všemi tasky
- potřebuješ rychle vypnout provoz
- řešíš hromadný error / ban risk

## Praktické tipy

- Nejdřív ověř **1 task end-to-end**, teprve pak škáluj
- Site u tasku musí sedět se site u profilu
- Po success koukni na webhook + [Stats](stats.md)
- Před větším dropem si exportuj tasky (backup)
- Po `STOP ALL` zkontroluj, že opravdu nic nedobíhá, než spustíš znovu

## Statusy

V tabulce uvidíš stav tasku (running, waiting, success, error, …). Čeká-li bot na SMS / 3DS / payment, sleduj UI i Discord webhook.

Detail shopů řeš v [Profiles](profiles.md) — správný profil je základ successu.
