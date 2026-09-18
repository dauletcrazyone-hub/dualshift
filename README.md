# DualShift

**PlayStation controllers, native on Windows.** Games see a plain Xbox 360
pad, so your DualSense or DualShock 4 works where it used to be ignored —
with rumble, gyro aiming, adaptive triggers and your own light bar colour.

### [⬇ Download the demo](../../releases/latest)

Free for 7 days, every feature unlocked. Windows 10 and 11, 64-bit.

[![Downloads](https://img.shields.io/github/downloads/dauletcrazyone-hub/dualshift/total?label=downloads&color=2FBF71)](../../releases/latest)

![Overview](docs/01-overview.png)

---

## What it does

**Makes the pad readable.** DualShift talks to the controller directly over
USB or Bluetooth and creates a virtual Xbox 360 controller in its place. A
game does not need to support PlayStation hardware — it sees the pad Windows
games have always understood. If a game does speak PlayStation, switch the
output to DualShock 4 and keep the native button icons and the touchpad.

**Rumble that arrives.** Force feedback from the game reaches the motors in
your hands the way it does on a console. The strength is adjustable.

**Gyro aiming.** The stick does the big turn, a light move of the hands does
the fine aim — the way console shooters are played, now on PC.

**Adaptive triggers.** A trigger can resist, fire in bursts, or click at the
moment of the shot. Tune it per game.

**Mouse mode.** One button turns the pad into a mouse: move the cursor with a
stick, the gyro or the touchpad, click with the shoulder buttons. Start a
film, scroll a feed, close a window — without getting up.

**On-screen keyboard.** Opens in its own window and types into whatever is
active — a browser, a search box, a chat. English, Russian and Kazakh
layouts.

**Per-game profiles.** Button mapping, stick dead zones and response curves,
light bar, rumble and trigger settings are saved per game and switch with it.

**14 interface languages**, light and dark theme.

| Live input and mapping | Mouse and keyboard |
|---|---|
| ![Buttons](docs/02-buttons.png) | ![Mouse](docs/04-mouse.png) |
| ![Axes](docs/03-axes.png) | ![Effects](docs/05-effects.png) |

## Requirements

- Windows 10 or 11, 64-bit
- DualSense, DualSense Edge, DualShock 4 — USB cable or Bluetooth
- ViGEmBus driver — **included in the installer**, it is offered during setup.
  Without it Windows cannot create the virtual controller.

## Installing

1. Download `DualShift Demo Setup.exe` from
   [Releases](../../releases/latest).
2. Run it. Windows will show a **SmartScreen warning** — the installer is not
   code-signed yet. Click **More info → Run anyway**. (A signing certificate
   costs real money; it is on the list.)
3. Agree to install ViGEmBus when the installer offers it. This step asks for
   administrator rights — the driver needs them, DualShift itself does not.
4. Connect the controller, open DualShift, press **Start bridge**.

To remove it: Windows Settings → Apps → DualShift → Uninstall. ViGEmBus is
left in place, other programs may be using it; it uninstalls the same way.

## Demo and full version

The demo runs **7 days with every feature unlocked** — nothing is disabled,
nothing is watermarked. After that it needs a key.

A key is issued for one computer: it is tied to the machine ID, so it keeps
working after a reinstall of the program, but not on a second PC.

**The quickest way to buy:** press **Buy a key** in the bottom-left corner of
the program. It opens [@DualShift_bot](https://t.me/DualShift_bot) in
Telegram with your computer code already filled in — pay with Telegram Stars
and the key arrives in the same chat, usually within seconds.

No Telegram? Write to **dauletcrazyone@gmail.com** with the computer code from
Settings, and the key comes back by mail.

## Privacy

DualShift works offline. There is no account, no telemetry and no analytics —
the trial dates and the key are stored on your own computer, and the program
sends nothing on its own. The only thing that ever leaves your PC is the
computer code, and only when you press **Buy a key** yourself: it goes into
the Telegram link so the bot knows which computer to issue the key for.

## Verifying the download

`DualShift Demo Setup.exe` 1.0.1 — 46.5 MB

```
SHA-256  f43afdc8b73cd5c14e3e184f9a8f3a363755cd3003a90a00dd155358b780efdc
```

Check it in PowerShell before running:

```powershell
Get-FileHash "$HOME\Downloads\DualShift Demo Setup.exe" -Algorithm SHA256
```

## Questions, bugs, requests

Open an [Issue](../../issues). Tell me the Windows version, the controller
model and how it is connected — USB or Bluetooth — and what the Overview
page shows.

---

Made by Daulet Kuanysh. DualShift is not affiliated with Sony Interactive
Entertainment or Microsoft. PlayStation, DualSense, DualShock and Xbox are
trademarks of their respective owners.
