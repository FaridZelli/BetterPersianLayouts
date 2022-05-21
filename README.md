# Better Persian Layouts
<img src="https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/banner.png" alt="" width="75%" align="center">
   
---
   
> **A collection of tweaks to improve Persian layout compatibility across various platforms**
---
## Persian digits on Windows 11 non-standard layout
   
Credit: [Farid Zellipour](https://github.com/FaridZelli/BetterPersianLayouts)
   
[Download Installer Here](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/source/Persian%20(Microsoft%20Non-Standard%20Layout)%20with%20Persian%20Digits.zip)
   
<details><summary>Language & region options (Expand)</summary>
  
![Settings Menu Options](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-settings.png?raw=true)
  
</details>
   
### Before:
![Windows 11 Keyboard (Before)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-before.png?raw=true)
### After:
![Windows 11 Keyboard (After)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-after.png?raw=true)

---

## Microsoft non-standard layout on X.Org
Credit: [Amir Hossein Shekari](https://github.com/vanenshi/xkb-windows-persian-configuration) and [Farid Zellipour](https://github.com/FaridZelli/BetterPersianLayouts)
   
### KDE Layout Selector:
![KDE Layout Selector (after mod)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-Layout-Selector.png?raw=true)
   
### Instructions:
> [Download and extract this archive](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/source/ir-XKB-Modified.zip)
   
> Open a Terminal in the directory
   
> Execute the following commands:
```
sudo mv ./ir /usr/share/X11/xkb/symbols
sudo nano /usr/share/X11/xkb/rules/evdev.xml
```
> Find the Persian section and paste the following text as such in [this example](https://github.com/FaridZelli/BetterPersianLayouts/blob/main/source/evdev_example.xml#L3340-L3371)
```
        <variant>
          <configItem>
            <name>pes_windows</name>
            <description>Persian (Microsoft)</description>
          </configItem>
        </variant>
        <variant>
          <configItem>
            <name>pes_windows_keypad</name>
            <description>Persian (Microsoft with Persian keypad)</description>
          </configItem>
        </variant>
```
### Before (standard layout):
![KDE Before (standard layout)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-Persian.png?raw=true)
  
![KDE Before (with Keypad)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-PersianKeypad.png?raw=true)
  
### After (non-standard layout):
![KDE After (non-standard layout)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-PersianMicrosoft.png?raw=true)
  
![KDE After (with Keypad)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-PersianMicrosoftKeypad.png?raw=true)
  
---
   
# Useful resources:
   
- [The Microsoft Keyboard Layout Creator (MSKLC)](https://support.microsoft.com/en-us/topic/906c31e4-d5ea-7988-cb39-7b688880d7cb)
- [MSKLC Link](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
- [X Keyboard Extension (XKB)](https://www.x.org/wiki/XKB/)
- [XKB Configuration Database](https://www.x.org/releases/individual/data/xkeyboard-config/)
- [XKB ArchWiki](https://wiki.archlinux.org/title/X_keyboard_extension)
- [Damiano Venturin's Guide to XKB](https://medium.com/@damko/a-simple-humble-but-comprehensive-guide-to-xkb-for-linux-6f1ad5e13450)
- [Unicode Charts](https://unicode.org/charts/)
- [Unicode Arabic Chart](https://unicode.org/charts/PDF/U0600.pdf)
- [Persian Computing Community](https://persian-computing.org/)
- [Persian Computing Wiki](https://persian-computing.org/wiki/)
- [Persian Computing Keyboard Wiki](https://persian-computing.org/wiki/Keyboard)
