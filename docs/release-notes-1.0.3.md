Free for 7 days, every feature unlocked. Windows 10 and 11, 64-bit.

**What's new in 1.0.3**

- **Profiles switch with the game.** Add a game to a profile in **Settings → Profiles** — pick it from the programs that are open, or choose its .exe. When the game comes to the front, DualShift turns its profile on; when you leave, the previous profile comes back. The Overview page shows which profile is on and which game turned it on.
- **Turbo.** Hold a button and the game gets rapid repeated presses, 2 to 20 a second. Choose the buttons on the **Buttons** page — face buttons, shoulders, stick clicks, the D-pad, and L2 and R2 too.
- **Low battery warning.** At 15% and again at 5%: a Windows notification and two short buzzes on the controller. It can be turned off in Settings → Behaviour.
- **Update notice.** At startup DualShift asks GitHub for the latest version number and tells you on the Overview page when a new one is out. Nothing else is sent; turn it off in Settings → About.
- **Test rumble.** A button on the Effects page runs the left motor, then the right one — no game needed.
- **Export and import profiles.** Save a profile to a file, load it on another PC or share it with a friend.
- **Profiles from the tray.** Right-click the tray icon → Profile, and switch without opening the window.

**What's inside**

- Xbox 360 output, so games that ignore PlayStation pads work — or DualShock 4 output, for games that show native icons and use the touchpad
- A live model of your controller, flat or in 3D
- Rumble from the game, adjustable strength
- Gyro aiming, adaptive triggers, your own light bar colour
- Keyboard keys from the controller: PS + Options for Alt+Tab, and your own combos
- Mouse mode: cursor from the stick, the gyro or the touchpad
- On-screen keyboard that types into any window — English, Russian, Kazakh
- Per-game profiles, dead zones and response curves, 14 interface languages

**Installing**

Run `DualShift Demo Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Just install on top — your settings, profiles and trial stay where they are.

**Verify the download**

SHA-256 `bd95174a2a3a094f8c48a5aeb067b95764a3fc2bb1639986fee638250be5af97`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Demo Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified.

Bugs and questions — open an Issue. Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
