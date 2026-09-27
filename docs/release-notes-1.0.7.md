**Free forever, Pro when you want more.** Windows 10 and 11, 64-bit.

**What's new in 1.0.7**

- **Gyro that actually aims.** Gyro sent into a stick used to be too weak for slow, careful aiming: games ignore a stick moved less than their own dead zone — about a quarter of the way — so small moves were lost and big ones came in jerks. Now DualShift makes up for that dead zone (the new *Game anti-dead zone* slider in the Gyro card, 0.25 by default), responds about 1.5 times stronger, and ignores sensor noise so the aim stays still when you do. Gyro into the mouse is 1.6 times stronger and moves smoothly at slow speeds. Existing profiles get the fix automatically.
- **The gyro calibrates itself.** When the controller lies still for a second and a half, DualShift finds the sensor's zero on its own — no more aim creeping sideways if you never pressed *Calibrate*. It never recalibrates while you hold the aim button. It can be turned off in the Gyro card.
- **Reset to defaults on every page.** Buttons, Axes, Mouse and Effects each have a *Reset to defaults* button that brings back the factory settings of that section only. Settings has *Reset everything*: all sections of the current profile and the app's behaviour. DualShift always asks first. Your profiles, game list, language, theme, Pro key and gyro calibration stay.

Everything from 1.0.6 is here too: gyro as a mouse, new adaptive trigger effects, the motion server for emulators and the Steam double-input warning.

**Installing**

Run `DualShift Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Install on top — your settings, profiles and key stay. If you had **DualShift Demo**, the installer removes it and puts the regular version in its place.

**Verify the download**

SHA-256 `47782d4d57a1cf1bf027e2c2381000c4a6ac6a464dc6824fb493ab1b9fb02e6e`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified. Adaptive trigger effects are encoded after TriggerEffectGenerator by John "Nielk1" Klein, MIT License.

Bugs and questions — open an Issue. Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
