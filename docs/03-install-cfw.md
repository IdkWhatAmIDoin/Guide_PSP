# 03 — installing ark-4

[← back to main guide](../README.md)

these steps are the same across **all psp models**. make sure you're on firmware 6.60 or 6.61 before starting.

---

## what you need

- memory stick pro duo (plugged into your reader)
- **[ARK-4 latest release](https://github.com/PSP-Archive/ARK-4/releases/latest)** — download the zip from github

---

## step 1 — copy files to memory stick

extract the ARK-4 zip. you need to copy two folders:

1. copy `ARK_01234` → `/PSP/SAVEDATA/` on your memory stick
2. copy `ARK_Loader` → `/PSP/GAME/` on your memory stick

your memory stick should look like this:

```
/
├── PSP/
│   ├── SAVEDATA/
│   │   └── ARK_01234/
│   └── GAME/
│       └── ARK_Loader/
└── ...
```

---

## step 2 — launch ark loader on your psp

1. eject the memory stick and slot it into your psp
2. go to `game → memory stick`
3. launch **ARK Loader**
4. wait for it to install — the psp will soft restart automatically

to verify it worked, go to `settings → system settings → system information`. you should see something like **ARK 4.xx.xx Live** next to the firmware version.

cfw is now running. 🎉

---

## step 3 — dealing with reboots

> [!WARNING]
> at this point you have **temporary** cfw — it resets on full power off (not sleep mode, just a full shutdown). you need to relaunch **ARK Loader** after each cold boot.

most people just leave their psp on sleep mode and rarely deal with this. but if you want to skip it entirely, go to [permanent cfw](04-permanent.md) next.

---

## what's next?

- make it permanent → [permanent cfw](04-permanent.md) ← recommended
- skip it for now → [playing games & plugins](05-games.md)
