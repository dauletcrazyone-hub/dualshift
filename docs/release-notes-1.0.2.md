Free for 7 days, every feature unlocked. Windows 10 and 11, 64-bit.

**What's new in 1.0.2**

- **Keyboard keys from the controller.** Hold PS and press a second button to send a key combination — leave a game with **PS + Options** (Alt+Tab), open Start with **PS + Create**, press Esc, show the desktop, change the volume. Works in games and in mouse mode. Every combo is yours to change on the **Mouse** page: pick the buttons and the keys from a list, or record your own combination. The held button does not reach the game while you hold it, and a normal short tap still does.
- **Games that run as administrator.** Windows blocks key presses into such games. DualShift now notices it and offers to restart with administrator rights, and there is a new switch in Settings → Behaviour: **Run as administrator**.
- **Only one copy runs at a time.** Starting DualShift again brings up the window that is already open, instead of a second bridge on the same controller.
- **Closing the window is clear now.** The close button asks whether to quit or keep running in the tray, and can remember the answer. Quit really quits — before, the process could stay in memory without a window.
- **Battery colours.** On the Overview bar and on the controller's light bar in *Battery* mode: blue when full, yellow in the middle, red when low.

**What's inside**

- Xbox 360 output, so games that ignore PlayStation pads work — or DualShock 4 output, for games that show native icons and use the touchpad
- A live model of your controller, flat or in 3D
- Rumble from the game, adjustable strength
- Gyro aiming, adaptive triggers, your own light bar colour
- Mouse mode: cursor from the stick, the gyro or the touchpad
- On-screen keyboard that types into any window — English, Russian, Kazakh
- Per-game profiles, dead zones and response curves, 14 interface languages

**Installing**

Run `DualShift Demo Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have 1.0.0 or 1.0.1? Just install on top — your settings, profiles and trial stay where they are.

**Verify the download**

SHA-256 `5f33e9675e52173bc48811590132043c54f879c3db02039db6cfe158fa184ab4`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Demo Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified.

Bugs and questions — open an Issue. Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
