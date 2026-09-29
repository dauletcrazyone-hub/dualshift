**Free forever, Pro when you want more.** Windows 10 and 11, 64-bit.

**What's new in 1.0.8**

- **The on-screen keyboard speaks every language of the app.** Russian, English, Kazakh, Kyrgyz, Chechen, German, Spanish, French, Polish, Arabic, Hindi, Chinese, Japanese and Korean — 14 layouts. It works like the keyboard on a phone: pick the languages you use on the Mouse page, and the 🌐 key switches between them; the language menu at the top has all of them. Long-press a letter to get its variants — é, ñ, ß, ё, أ. Korean jamo join into syllables as you type (ㅎ ㅏ ㄴ → 한), Japanese has a kana grid with a ゛゜小 key for dakuten and small kana, Shift gives katakana, and Chinese types through the Windows Pinyin input method. A double tap on Shift turns on caps lock. The window never takes focus, so the text still lands in the browser or the search box.
- **Turn off the controller from the PC.** Over Bluetooth, the new *Turn off controller* button on the Overview page — or in the tray menu — puts the DualSense to sleep at once. No more holding PS for ten seconds.
- **Auto power-off when idle.** Settings → Controller → *Turn off the controller when idle*: after 5 to 60 minutes without a touch the controller turns itself off and saves the battery. Off by default; Bluetooth only.
- **Connection notice with the battery level.** When the controller connects while DualShift is in the tray, Windows shows *DualSense connected · Bluetooth · battery 80%*. Can be turned off in Settings.
- **Switch profiles right in the game** *(Pro)*. Hold the microphone button and press left or right on the D-pad — the next profile turns on and the controller gives a short buzz. The D-pad press does not reach the game.

Everything from 1.0.7 is here too: gyro that aims with small moves, gyro self-calibration and *Reset to defaults* on every page.

**Installing**

Run `DualShift Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Install on top — your settings, profiles and key stay. If you had **DualShift Demo**, the installer removes it and puts the regular version in its place.

**Verify the download**

SHA-256 `2410371f64f6d24b47bfbd82f213a56ece84c3ec5b975bab80764fb447c97334`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified. Adaptive trigger effects are encoded after TriggerEffectGenerator by John "Nielk1" Klein, MIT License.

Bugs and questions — open an Issue. Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
