# Drupal core patches

Curated **Drupal core** patches used by [Varbase](https://www.drupal.org/project/varbase),
with **one git branch per Drupal core major.minor version** (e.g. `10.6.x`, `11.3.x`).

Each branch's `composer.json` declares the core patches under
`extra.patches."drupal/core"`. They are applied by
[cweagans/composer-patches](https://github.com/cweagans/composer-patches) when this
package is required. [Varbase Patches](https://github.com/Vardot/varbase-patches)
requires this package instead of carrying the core patches itself.

## Usage

```bash
composer require vardot/drupal-core-patches:~11.3.0
```

## Branch per Drupal core major.minor

| Drupal core | Branch    |
|-------------|-----------|
| ~10.6       | `10.6.x`  |
| ~11.3       | `11.3.x`  |

Add a new branch (e.g. `11.4.x`) when supporting a new Drupal core minor and move the
relevant core patches into its `composer.json`.
