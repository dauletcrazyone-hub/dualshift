**Free forever, Pro when you want more.** Windows 10 and 11, 64-bit.

**What's new in 1.0.9**

- **Help, right in the app.** A new Help page with a four-step quick start, answers to the common questions — the game doesn't see the controller, every press registers twice, stick drift, gyro aim, Bluetooth, emulators, Pro — and a search box. Every page has a **?** button that opens its own section, and the bottom of the page links to the video guide, Telegram and bug reports. Available in all 14 languages.
- **Keyboard and mouse for games without controller support** *(Pro)*. Buttons page → *Keyboard and mouse*: any button can press a key or a mouse button, the left stick becomes WASD or the arrow keys, the right stick moves the mouse. *Shooter layout* fills everything in with one click. Keys are held as long as the button and are sent as scan codes, so DirectInput and Raw Input games see them; whatever goes to the keyboard no longer reaches the game as a controller.
- **Start with Windows.** Settings → *Start with Windows*: DualShift starts minimized to the tray and turns the bridge on by itself.
- **Battery on the tray icon.** A small bar on the tray icon shows the controller's charge — green, yellow, red, blue while charging.
- **What's new.** After an update, a short window lists what changed and opens Help if you want.

Everything from 1.0.8 is here too: the on-screen keyboard in 14 languages, turning the controller off over Bluetooth, auto power-off when idle and switching profiles with the mic button.

**Installing**

Run `DualShift Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Install on top — your settings, profiles and key stay. If you had **DualShift Demo**, the installer removes it and puts the regular version in its place.

**Verify the download**

SHA-256 `00fbb0cf9add27c9bf5a497320f41e59437accfd4e872d3f22701c1cd1d47917`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified. Adaptive trigger effects are encoded after TriggerEffectGenerator by John "Nielk1" Klein, MIT License.

Bugs and questions — open an Issue. Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
