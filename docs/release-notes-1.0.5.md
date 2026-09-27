**Free forever, Pro when you want more.** Windows 10 and 11, 64-bit.

**What's new in 1.0.5 — polish**

- **Real button symbols.** Cross, circle, square and triangle are now drawn like on the controller — the same size and weight everywhere: in the button layout, the turbo buttons and every list where you pick a button.
- **Smooth, rounded sliders.** A rounded track and a round knob that glides to its new value, grows under the cursor and jumps to wherever you click on the track.
- **Smooth scrolling.** The mouse wheel glides through the pages instead of jumping.
- **No more settings changed by accident.** Scrolling a page over a slider or a list used to change its value. Now the wheel scrolls the page, and a slider or list reacts to the wheel only after you click it.
- **Faster.** Switching the profile, the language or the theme is about ten times quicker, the window opens sooner, and scrolling redraws less.
- **Fixed:** after switching pages very quickly, a page could stay a few pixels lower than it should.
- **Fixed:** the cursor speed on the Mouse page showed its unit in Russian letters in every language.
- **The version is in the file properties.** Right-click `DualShift.exe` → Properties → Details shows 1.0.5, and so does Windows Settings → Apps.

Everything from 1.0.4 is here too: the free version, DualShift Pro, the new look, the stick drift check and the light bar effects.

**Installing**

Run `DualShift Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Install on top — your settings, profiles and key stay. If you had **DualShift Demo**, the installer removes it and puts the regular version in its place.

**Verify the download**

SHA-256 `63494d55f6771d15413ae1fc148ba13765b9d89f0177ac3fac8eeec1f993dcd4`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified.

Bugs and questions — open an Issue. Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
