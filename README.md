# 🚀 Win32 GDI Weapon (Invicible)

A lightweight and dynamic visual presentation program (GDI screen effect) built entirely using raw **Win32 API (C++)**. The application generates an ultra-smooth, chaotic bounce effect over the desktop surface, inspired by the classic *Mrs. Major* aesthetic.

---

## ✨ Features
* **Dynamic Image Spam**: 12 independent, randomly scaled instances of your custom image flying and bouncing simultaneously.
* **Intense GDI Glitches**: Random screen shaking, screen melting, and rapid inverted flashes (`DSTINVERT`).
* **Audio Loop Support**: Continuous, non-blocking background audio playback using a local `.wav` file.
* **Full Personalization**: Native integration of custom application icons and an animated system cursor.

---

## 📦 Required Asset Setup

To run properly, the pre-compiled `.exe` file requires specific asset files to be placed in a dedicated system folder. Before launching the application, please follow these steps:

1. Press `Win + R`, type `%LocalAppData%` and hit **Enter** to open your local app data folder.
2. Create a new folder named exactly: **`xiiudsh`**
3. Place the files i published (ex. excursor.ani is cursor)
   * `thetruth.bmp` — Your main image (must be saved via Paint as a **24-bit or 32-bit BMP bitmap**)
   * `clingclang.wav` — Your background audio loop file
   * `excursor.ani` — Your animated mouse cursor
   * `fileico.ico` — Your application icon file

---

## 🚀 How to Run

1. Go to the **main branch** on the right side of this GitHub repository and download the compiled `invicible.exe` and other files
2. Ensure your assets are correctly placed inside the `AppData\Local\xiiudsh\` folder.
3. Double-click **`invicible.exe`** to open the controller window, then click the **"Uruchom efekt graficzny"** button.

---

## 🛑 Safe Exit (Emergency Brake)

The program includes an instant safety kill-switch to protect your workflow. To immediately stop all GDI effects, mute the audio, and terminate the process:
* Press the **`ESC`** key on your keyboard.

*The desktop will automatically redraw back to its original state, and your mouse cursor will instantly return to normal.*

---

## ⚠️ Antivirus Notice (False Positives)
Due to the nature of GDI manipulation (drawing directly onto the screen's HDC) and creating overlay windows (`WS_EX_LAYERED`), modern antivirus software (e.g., Windows Defender, Avast) might flag the `.exe` file as a threat (**False Positive**). If the application gets blocked or instantly closes, add the program or the folder to your antivirus exclusion list.
