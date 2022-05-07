# Better Persian Layouts
![Better Persian Layouts](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/banner.png?raw=true)
   
> ### A collection of tweaks to improve Persian layout compatibility across various platforms
---
- # Persian digits on Windows 11 non-standard layout
   
Credit: [Farid Zellipour](https://github.com/FaridZelli/BetterPersianLayouts)
   
## [Download Installer Here](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/source/Persian%20(Microsoft%20Non-Standard%20Layout)%20with%20Persian%20Digits.zip)
   
<details><summary>Settings Menu Options</summary>
  
![Settings Menu Options (Expand)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-settings.png?raw=true)
  
</details>
   
> ### ```Before:```
![Windows 11 Keyboard (Before)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-before.png?raw=true)
> ### ```After:```
![Windows 11 Keyboard (After)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-after.png?raw=true)

---

- # Microsoft non-standard layout on X.Org
Credit: [Amir Hossein Shekari](https://github.com/vanenshi/xkb-windows-persian-configuration) and [Farid Zellipour](https://github.com/FaridZelli/BetterPersianLayouts)
   
> ### ```KDE Layout Selector:```
![KDE Layout Selector (after mod)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-Layout.png?raw=true)
   
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
> ### ```Before (standard layout):```
![KDE Before (standard layout)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-before1.png?raw=true)
  
![KDE Before (with Keypad)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-before2.png?raw=true)
  

> ### ```After (non-standard layout):```
![KDE After (non-standard layout)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-after1.png?raw=true)
  
![KDE After (with Keypad)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/KDE-after2.png?raw=true)
  
