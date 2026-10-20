# Profiles

A profile = address / account / payment details for a specific shop. Without a correct profile, tasks won’t run reliably.

## Creating a profile

1. Open **Profiles**
2. Click **New profile**
3. Select the **site**
4. Name the profile however you like, **or**
5. You can auto-fill a profile from the Generator — generated accounts sync into Profiles so you can turn them into ready profiles quickly

## Random details (CZ / SK)

On each profile you can fill random details by country:

- Enter `cz` or `sk` in the relevant field
- The bot fills the data for you

Great for quick address generation. Still double-check that the address makes sense for the shop (especially Rohlik).

## Per-site tips

### CDMC

Shoptet-based → you can run **guest** (no CDMC-specific account required).

- **Always** set a **pickup point ID** on every profile
- Guest is convenient; for important drops an account is usually more stable

### Alza

- **Run with accounts** — guest can bug / error out
- The module is mainly ready for **Pokémon** products
- Create accounts in the [Generator](generator.md) — they sync into Profiles
- **Don’t forget to enable Alzaboxy**

### Toredo

Same logic as CDMC (Shoptet):

- Guest is possible
- Always set **pickup point ID**
- Account = better session handling

### Dobré knihy

- You can enable **store pickup** at the bottom
- Guest works, but **prefer accounts** — better session handling, fewer things that can break

### Rohlik

- **Strongly recommended** to use real accounts in the profile
- Rohlik is inconsistent with products/addresses — some regions see stock, others don’t
- Fill the address **exactly** (street, city, ZIP) as on the account to avoid unnecessary errors

### Černý rytíř

- You must **create / generate accounts yourself**
- Only **real existing accounts** can be added — no guest checkout
- Store **pickup** is available
- **Don’t forget to select a pickup point**

### Shopify

- Fill in **CC details** (card) on the profile
- Without correct payment details, checkout won’t complete

## Quick reference

| Shop | Guest | Account | Extra |
|------|-------|---------|-------|
| CDMC / Toredo | OK | Better | Pickup point ID |
| Alza | Not recommended | Yes | Alzaboxy + generator |
| Dobré knihy | OK | Better | Pickup toggle |
| Rohlik | — | Strongly yes | Exact address |
| Černý rytíř | No | Required | Pickup point |
| Shopify | — | — | CC details |

**Export** profiles after setup — see backups in [Download & launch](download-and-launch.md).
