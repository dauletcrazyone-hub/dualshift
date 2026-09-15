# DualShift 1.0.0 — demo

Free for 7 days, every feature unlocked. Windows 10 and 11, 64-bit.

**What's inside**

- Xbox 360 output, so games that ignore PlayStation pads work — or DualShock 4
  output, for games that show native icons and use the touchpad
- Rumble from the game, adjustable strength
- Gyro aiming, adaptive triggers, your own light bar colour
- Mouse mode: cursor from the stick, the gyro or the touchpad
- On-screen keyboard that types into any window — English, Russian, Kazakh
- Per-game profiles, dead zones and response curves, 14 interface languages

**Installing**

Run `DualShift Demo Setup.exe`. Windows shows a SmartScreen warning — the
installer is not code-signed yet: **More info → Run anyway**. Agree to install
the bundled ViGEmBus driver when the installer offers it; without it Windows
cannot create the virtual controller.

**Verify the download**

```
SHA-256  7985c3909b9886fcddecc880c96096891e31f10c4dfb9cd4bf7325a81fae75f5
```

```powershell
Get-FileHash "$HOME\Downloads\DualShift Demo Setup.exe" -Algorithm SHA256
```

Bugs and questions — open an Issue. Please say which Windows version and
controller you have, and whether it is connected by USB or Bluetooth.
