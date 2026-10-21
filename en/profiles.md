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

## Tips by site

**CDMC:**

Shoptet-based → you can run **guest** (no CDMC-specific account required).

- **Always** set a **pickup point ID** on every profile
- Guest is convenient; for important drops an account is usually more stable
- After a successful checkout a **payment link** is generated — find it in the bot or in the webhook
- You need to **pay ASAP**, but there should be a short hold

**Alza:**

- **Run with accounts** — guest can bug / error out
- The module is mainly ready for **Pokémon** products
- Create accounts in the [Generator](generator.md) — they sync into Profiles
- **Don’t forget to enable Alzaboxy**
- Payment is **only after pickup from the Alzabox**

**Toredo:**

Same logic as CDMC (Shoptet):

- Guest is possible
- Always set **pickup point ID**
- Account = better session handling
- After checkout a **payment link** is generated in the bot or webhook
- If you want the order, you need to **pay it**

**Dobré knihy:**

- You can enable **store pickup** at the bottom
- Guest works, but **prefer accounts** — better session handling, fewer things that can break
- Either store pickup, **or** a **payment link** is generated and must be paid **ASAP**

**Rohlik:**

- **Strongly recommended** to use real accounts in the profile
- Rohlik is inconsistent with products/addresses — some regions see stock, others don’t
- Fill the address **exactly** (street, city, ZIP) as on the account to avoid unnecessary errors
- Payment is **on delivery to the address**
- Delivery time is taken from the **standard slot offer** available for your address at the moment of checkout

**Černý rytíř:**

- You must **create / generate accounts yourself**
- Only **real existing accounts** can be added — no guest checkout
- Store **pickup** is available
- **Don’t forget to select a pickup point**
- A **payment link** is generated and clicking it takes you straight into payment — again, pay **ASAP**
- Alternative: **pickup**

**Shopify:**

- The **only module** where you need to fill in **card details** on the profile
- Without correct payment details, checkout won’t complete
- For **test checkouts**, feel free to freeze the card or keep an insufficient balance

**Export** profiles after setup — see backups in [Download & launch](download-and-launch.md).
