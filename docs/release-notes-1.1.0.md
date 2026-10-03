**Free forever, Pro when you want more.** Windows 10 and 11, 64-bit.

**1.1.0 is a stability release.** The whole code base went through a review and a stress test — every page in 14 languages and both themes, profiles, resets, the keyboard, notifications, and thousands of random controller states through the bridge in every mode. Here is what was fixed.

**Fixed**

- **The bridge no longer dies silently.** Any unexpected error inside the bridge used to stop it for good: the button still said *Stop bridge*, but the game lost the controller until you restarted DualShift. Now the bridge reconnects by itself within a second and writes the details to an error log.
- **A damaged settings file no longer wipes your profiles.** One broken value used to reset *all* profiles to defaults, and some broken values slipped through and later stopped the bridge (for example, a light bar colour out of range). Now only the broken value falls back to its default, everything else is kept, and a copy of the old file is saved as `profiles.broken.json`.
- **Gyro calibration is saved and says “Done”.** The result was handled on the wrong thread: the new zero point was not saved until some other change, and the *Done* message never appeared.
- **Mic button + ← / → no longer turns on mouse mode.** Switching profiles with the mic button also toggled mouse mode if it used the same button.
- **No crash on exit.** Closing DualShift while the update check or the Pro payment check was still running, or while the bridge was slow to stop, could crash it; a locked settings file could leave the process hanging without a window. All of these are handled now.
- **No crash when changing the language during a payment check.** Changing the language or theme while *Check payment* was running destroyed a working thread.
- **The emulator motion server (DSU)** no longer spins the CPU if its network socket keeps failing.
- **Settings are saved even when the file is busy** (antivirus, OneDrive): DualShift retries instead of losing the change.
- **A sharp icon everywhere.** The old `.ico` held a single 256 px image that Windows shrank down to 16 px in the tray and on the taskbar; now every size is drawn on its own.

**New**

- **Microphone button mutes the Windows microphone** — like on PS5. Press it: nobody hears you in Discord, games or calls, and the button on the controller lights up. Press again to unmute. Settings → Controller.
- **Backup of all settings** to one file and **restore** from it — after reinstalling Windows or on a new PC. Settings → Backup.
- **Error log.** Help → *Error log* opens it, so you can attach it to a bug report.
- **New app icon.**

**Installing**

Run `DualShift Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Install on top — your settings, profiles and key stay. If you had **DualShift Demo**, the installer removes it and puts the regular version in its place.

**Verify the download**

SHA-256 `fcf39ada0a97270a9b42b4fa1ea2dd5d4a2e4b2ffcc63e34bb0caa8fa54c31f2`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified. Adaptive trigger effects are encoded after TriggerEffectGenerator by John "Nielk1" Klein, MIT License.

Bugs and questions — open an Issue and attach the error log (Help → Error log). Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
