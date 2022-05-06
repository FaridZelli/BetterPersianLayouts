# Better Persian Layouts
![Better Persian Layouts](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/banner.png?raw=true)
   
> ### A collection of tweaks to improve Persian layout compatibility across various platforms
---
- # Persian digits on Windows 11
## [Download Installer Here](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/source/Persian%20(Microsoft%20Non-Standard%20Layout)%20with%20Persian%20Digits.zip)
   
<details><summary>Settings Menu Options</summary>
  
![Settings Menu Options](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-settings.png?raw=true)
  
</details>
   
> ### ```Before:```
![Windows 11 Keyboard (Before)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-before.png?raw=true)
> ### ```After:```
![Windows 11 Keyboard (After)](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/images/windows11-after.png?raw=true)

---

- # Microsoft layout on X.Org
Credit: [Amir Hossein Shekari](https://github.com/vanenshi/xkb-windows-persian-configuration)
### Instructions:
> [Download and extract this archive](https://github.com/FaridZelli/BetterPersianLayouts/raw/main/source/ir-XKB-Modified.zip)
   
> Open a Terminal in the directory
   
> Execute the following commands:
```
sudo mv ./ir /usr/share/X11/xkb/symbols
sudo nano /usr/share/X11/xkb/rules/evdev.xml
```
> Find the Persian section and paste the following text as such in this example
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
