# 05 — playing games & plugins

[← back to main guide](../README.md)

ark-4 is installed — here's what to do with it.

---

## playing iso games

create an `ISO/` folder at the root of your memory stick if it doesn't exist already.

```
/
├── ISO/       ← put your .iso and .cso files here
├── PSP/
└── ...
```

games show up automatically under `game → memory stick`.

> [!NOTE]
> ARK-4 supports `.iso`, `.cso`, `.zso`, `.jso`, `.cso v2`, and `.dax` formats out of the box via the built-in Inferno driver.

---

## plugins

ARK-4 handles plugins differently from PRO/ME — it has a built-in plugin manager in the custom launcher instead of manually editing text files.

**the easy way (ark custom launcher):**
1. copy your `.prx` plugin file to `seplugins/` on your memory stick
2. in ARK, go to `extras → custom launcher`
3. use the file manager to navigate to your plugin and install it

**the manual way (still works):**

plugins live in `seplugins/` and are configured via text files:

| file | when it loads |
|---|---|
| `game.txt` | during games |
| `vsh.txt` | on the xmb (home screen) |
| `pops.txt` | during ps1 games |

each line is a path to a `.prx` file followed by `1` (on) or `0` (off):

```
ms0:/seplugins/cwcheat/cwcheat.prx 1
ms0:/seplugins/remotejoy.prx 0
```

---

## useful plugins

- **cwcheat** — in-game cheat codes
- **remotejoy** — mirror your psp screen to pc
- **popcorn** — improved ps1 compatibility (built into ark-4)
- **categories lite** — organize your game list into folders

---

## updating ark-4

ark-4 can update itself over wifi:

1. go to `ark-4 updater` on the xmb
2. select **update via internet**

or manually: download the latest zip, copy the `UPDATE` folder to `/PSP/GAME/` and run it from the game menu.

---

## recovery menu

hold `L` while booting (with cipl installed) to open the recovery menu. from here you can toggle plugins, fix settings, and recover from most soft bricks.

---

## you're all set 🎉

if something breaks, the [ARK-4 wiki](https://github.com/PSP-Archive/ARK-4/wiki) and [wololo.net](https://wololo.net) are your best friends.
