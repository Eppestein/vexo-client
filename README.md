# Vexo Client (Fabric, Minecraft 1.21.11)

Build: install JDK 21, then in this folder run `gradle wrapper` (once) and `./gradlew build`
(Windows: `gradlew.bat build`). The jar ends up in `build/libs/` (use the one WITHOUT `-sources`).
Needs Fabric Loader 0.18.1+ and Fabric API for 1.21.11 in your mods folder.

* Right Shift: open menu (rebindable in Controls). Click header to collapse, click rows to toggle, Esc closes.
* Config: `.minecraft/config/vexoclient.json`
* Logo next to names: always on your own name. For OTHER players, the server must also run
  this same jar (it relays who uses Vexo). Without it, only you see your own logo.
