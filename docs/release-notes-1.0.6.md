**Free forever, Pro when you want more.** Windows 10 and 11, 64-bit.

**What's new in 1.0.6**

- **Gyro as a mouse.** On the Axes page, send the gyro into the **mouse** instead of a stick: tilting the controller moves the aim pixel by pixel, the way Steam Input and JoyShockMapper do it. Most PC shooters take mouse movement and the controller at the same time. Works with "While L2 is held" too, so the gyro only aims while you aim down sights. Free.
- **New adaptive trigger effects.** Besides resistance, semi-automatic and automatic: **progressive resistance** that builds up like a brake pedal, a **bow** string that snaps back, and a **galloping** rhythm. All effects now use the official DualSense firmware encodings, which the controller checks for safe values. The frequency slider only appears for the effects that use it.
- **Motion for emulators (DSU).** Settings → Emulators → Motion server. Cemu, Ryujinx, Dolphin, Citra and other emulators get the controller's gyro, buttons, sticks and touchpad over the standard DSU (cemuhook) protocol — the same one DS4Windows uses. It listens on this computer only: 127.0.0.1, port 26760. If DS4Windows already holds the port, DualShift says so.
- **Warning about double input from Steam.** While Steam is running, the Overview page explains what to do if a Steam game registers presses twice.
- **Game Bar combos.** New ready-made keyboard combos: take a game screenshot, record the last 30 seconds, start or stop a recording, mute the microphone in a call.
- **Fixed:** the interface language reset to Russian after a restart for 11 of the 14 languages — German, Spanish, French, Polish, Kyrgyz, Chechen, Arabic, Hindi, Japanese, Chinese and Korean.
- **Fixed:** a ready-made combo written with Win in the middle (Win+Shift+S) lost its description after a restart and showed up twice in the list.

**Installing**

Run `DualShift Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Install on top — your settings, profiles and key stay. If you had **DualShift Demo**, the installer removes it and puts the regular version in its place.

**Verify the download**

SHA-256 `4c7949ab6dc1c1357a4d04e99eae4069c0e7799c532a2a1a4249619d92b7f55d`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified. Adaptive trigger effects are encoded after TriggerEffectGenerator by John "Nielk1" Klein, MIT License.

Bugs and questions — open an Issue. Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
