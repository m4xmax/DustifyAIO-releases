# Tasks

A task = one running session (monitor / checkout) tied to a site, profile, and optionally a proxy group.

## Creating tasks

1. Open **Tasks**
2. Click **Create tasks**
3. Add individual tasks or **task groups**
4. You can **rename** tasks freely
5. Create **multiple tasks for the same site** (different products, profiles, delays)

## Settings

On tasks you can configure, among other things:

- **Custom monitor delay**
- **Error delay**
- Site / product
- Profile
- Proxy group

Tune delays to the shop and proxy quality. If you’re unsure, start with defaults and adjust based on behavior.

## Proxies on tasks

Pick a proxy group on the task (groups are created under [Proxies](proxies.md)).

- **Alza:** running on proxies is recommended, but not required
- On harder shops (e.g. Shopify / CF), good proxies matter more for success rate

## STOP ALL (panic button)

**STOP ALL** immediately stops **every** running task.

Use it when:

- something is going wrong across all tasks
- you need to shut down quickly
- you’re dealing with mass errors / ban risk

## Practical tips

- Validate **1 task end-to-end** before scaling
- Task site must match the profile site
- After success, check the webhook + [Stats](stats.md)
- Export tasks before a big drop (backup)
- After `STOP ALL`, confirm nothing is still running before you start again

## Statuses

The table shows task state (running, waiting, success, error, …). If the bot waits for SMS / 3DS / payment, watch both the UI and Discord webhooks.

Shop-specific setup lives mainly in [Profiles](profiles.md) — a correct profile is the foundation of success.
