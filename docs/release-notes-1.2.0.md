**Free forever, Pro when you want more.** Windows 10 and 11, 64-bit.

**1.2.0 speaks 20 languages and lets you pick your colour.**

**New**

- **Six new languages: Portuguese (Brazil), Turkish, Uzbek, Indonesian, Italian and Ukrainian.** The whole program and the built-in help are translated, and the on-screen keyboard gets matching layouts: Turkish ı/İ and ğ ş ç, Ukrainian ї є ґ, Uzbek oʻ gʻ, Portuguese ç and ã, Italian à è ò. That makes 20 interface languages.
- **DualShift speaks your language from the first launch.** A new install picks the language of your Windows by itself. Before, everybody started in Russian and had to find the language switch.
- **Accent colours.** Blue, violet, teal, green, orange, pink or red — Settings → Appearance. The whole window changes at once, in the dark and the light theme.
- **Button test.** A new card on the Overview page: press every button and push the sticks in every direction, and whatever works lights up green. It is a quick way to check a used controller or find a button that no longer responds.
- **Battery time left.** On battery, the Overview page and the tray icon show roughly how long the charge will last — for example *≈ 3 h 20 min* — worked out from how fast it is going down right now.

**Fixed**

- Some strings from tables — mouse button names, stick clicks, the installer — were never checked for missing translations. Now every language is compared against the full catalogue, so no string is left untranslated.
- A settings file from an older version is read correctly: new options take their defaults instead of breaking the next save.

**Installing**

Run `DualShift Setup.exe`. Windows shows a SmartScreen warning — the installer is not code-signed yet: **More info → Run anyway**. Agree to install the bundled ViGEmBus driver when the installer offers it; without it Windows cannot create the virtual controller.

Already have an earlier version? Install on top — your settings, profiles, language and key stay. If you had **DualShift Demo**, the installer removes it and puts the regular version in its place.

**Verify the download**

SHA-256 `75f1eb85efe717ce92b4d9f28c6a1fcae8d463f26cfe04a088ef75022e7ebdd3`

```powershell
Get-FileHash "$HOME\Downloads\DualShift Setup.exe" -Algorithm SHA256
```

3D model: "Playstation 5 Dualsense" by AHarmlessPotato (Sketchfab), CC BY 4.0, modified. Adaptive trigger effects are encoded after TriggerEffectGenerator by John "Nielk1" Klein, MIT License.

Bugs and questions — open an Issue and attach the error log (Help → Error log). Please say which Windows version and controller you have, and whether it is connected by USB or Bluetooth.
