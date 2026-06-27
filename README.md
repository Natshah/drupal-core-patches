# Drupal core patch files

> **Why this package:** `vardot/drupal-core-patches` is required by [`vardot/varbase-patches`](https://github.com/Vardot/varbase-patches) so that [Varbase](https://www.drupal.org/project/varbase) can upgrade to the latest Drupal core versions. It maintains the right set of working Drupal **core** patches **per Drupal core version** (one branch per major.minor), so each Varbase line automatically gets the patches that apply to its Drupal core.

Flat store of the Drupal **core** `.patch` files used by Varbase, kept on this `patches`
branch and referenced by raw URL from the per-core-minor branches (`11.3.x`, `10.6.x`, …):

```
https://raw.githubusercontent.com/Vardot/drupal-core-patches/refs/heads/patches/<file>.patch
```
