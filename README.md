# 🎡 Fairground Online — BepInEx Mod Loader Framework

Das offizielle, vorkonfigurierte **BepInEx 6 (IL2CPP x64)** Mod-Loader-Paket für **Fairground Online**.  
Einfach entpacken und sofort loslegen — keine Programmierkenntnisse oder komplizierte Einrichtung erforderlich!

---

## 🚀 Schnellanleitung (In 30 Sekunden startklar)

### 1. Herunterladen
Lade die neueste Version als `.zip`-Datei unter **[Releases](https://github.com/BlackMautz/Fairground-Online-BepInEx/releases)** herunter.

### 2. Entpacken
Entpacke den gesamten Inhalt der ZIP-Datei direkt in dein **Fairground Online Hauptverzeichnis** (dort, wo sich die `Fairground Online.exe` befindet).

> **Steam-Standardpfad:**  
> `C:\Program Files (x86)\Steam\steamapps\common\Fairground Online`  
> *(oder auf deiner entsprechenden Festplatte, z. B. `F:\steam\steamapps\common\Fairground Online`)*

Dein Spielordner sieht danach so aus:
```text
Fairground Online/
├── BepInEx/
│   ├── config/
│   ├── core/
│   └── plugins/   <-- Hier kommen deine Mods hinein!
├── Fairground Online.exe
├── winhttp.dll
└── doorstop_config.ini
```

### 3. Spiel einmal starten
Starte das Spiel ganz normal über Steam. BepInEx generiert beim ersten Start automatisch alle benötigten Schnittstellen im Hintergrund.

---

## 🧩 Wie installiere ich Mods?

1. Lade dir eine beliebige Mod für *Fairground Online* herunter (z. B. eine `.dll`-Datei).
2. Schiebe die Mod-Datei einfach in den Ordner:
   ```text
   Fairground Online / BepInEx / plugins /
   ```
3. Spiel starten — die Mod ist sofort aktiv!

---

## ⚙️ Kompatibilität
- **Spiel:** Fairground Online (Steam Version)
- **Architektur:** 64-Bit (x64 Unity IL2CPP)
- **Multiplayer:** 100 % kompatibel

---

## ❓ Häufige Fragen & Hilfe

**Q: Mein Spiel startet nicht mehr oder zeigt einen schwarzen Bildschirm?**  
> Vergewissere dich, dass die `winhttp.dll` und `doorstop_config.ini` direkt neben der `Fairground Online.exe` liegen und nicht in einem Unterordner.

**Q: Wie deinstalliere ich BepInEx wieder?**  
> Lösche einfach den Ordner `BepInEx` sowie die beiden Dateien `winhttp.dll` und `doorstop_config.ini`. Dein Spiel ist dann wieder komplett im Originalzustand.

---
*Erstellt für die Fairground Online Community von [BlackMautz](https://github.com/BlackMautz).*
