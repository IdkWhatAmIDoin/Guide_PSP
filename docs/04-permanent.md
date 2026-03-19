# 04 — permanent cfw

[← back to main guide](../README.md)

permanent cfw means ARK-4 loads automatically on every boot — no more relaunching ARK Loader after a power off. works on **all psp models**.

> [!NOTE]
> you need to have temporary ARK-4 running first. if you haven't done that yet, go to [installing ark-4](03-install-cfw.md).

---

## step 1 — copy the cipl flasher to your memory stick

1. open the ARK-4 zip you downloaded earlier
2. find the `ARK_cIPL` folder inside `/PSP/GAME/`
3. copy it to `/PSP/GAME/` on your memory stick

---

## step 2 — flash cipl

with ARK-4 temporarily running:

1. go to `game → memory stick`
2. launch **ARK cIPL Flasher**
3. follow the on-screen prompts

> [!WARNING]
> this writes to your psp's internal flash memory. risk of bricking is very low but keep your battery charged and don't interrupt it.

after flashing, ARK-4 will load automatically on every boot. you're done.

---

## bonus — brick protection

ARK-4's cipl includes recovery built in. if your psp ever soft bricks, you can recover it by holding `L` while powering on to boot into a recovery mode. way safer than the old PRO-C2 cipl.

---

## what's next?

→ [playing games & plugins](05-games.md)
