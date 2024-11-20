<!---
<p>
  <img src="images/logo.png" width="100" height="100" align="right" />
</p>
--->
*Read this in other languages: [Rromani](README.rom.md), [Română](README.ro.md).*

This project provides custom International Standard Romani keyboard layouts for Windows and MacOS systems, allowing easy access to the following special characters: 

| morpho-graphs | meta-notations | fricative / affricate  | unrounded vowels |
|----|----|----|----|
| ç, θ | ʒ, ǎ, ě, ǐ, ǒ, ǔ | ś, ć, ź | ä, ë, ï, ö, ü |

The International Standard Romani aphabet was devised by Romani linguist Marcel Courthiade and adopted by the International Romani Union at the Fourth Romani World Congress in Warsaw, Poland in April 1990.

# Getting Started

These instructions will help you install the keyboard layout on your computer. You should not need to close any programs or restart your computer in order for the new keyboard layout to be recognized.

- [Windows installation instructions](#windows-installation)
- [MacOS installation instructions](#macos-installation)
- [Keyboard reference guide](#keyboard-reference-guide)

# Windows Installation

1. Download the Windows installer [**here**.](Romani_IRU_Windows.zip) Open the .ZIP file and double-click on the installer named **"Install_Rromani_Keyboard_IRU.exe"**.

<p>
  <img src="images/language_bar.png" align="right" />
</p>

2. The new keyboard layout should now appear in the list of languages in the language bar (in the taskbar) as "OL Rromani" (in Windows 7) or "ROM Rromani" (in Windows 8 or newer). If you don't see the Language bar, right-click the taskbar, select **Toolbars,** and then click **Language bar.**


*NOTE: It is possible that the Romani keyboard will not appear in the list of languages in the Windows Control Panel 
"Keyboards and Languages" tab. This is a known issue and does not impair the functionality of the keyboard layout.*


## Windows Romani Custom Locale
Windows uses settings called "Locales" to determine how dates and numbers are displayed on your computer. To install a Romani language locale for Windows:
1. Download the install package [**here**.](Romani_IRU_Windows.zip) 
2. Open the .ZIP file and double-click on the installer named **"Install_Locale_Rromani_IRU.msi"**. 
3. Once the installer has finished, click the open the **Control Panel** and click the **Clock, Language, and Region** icon, then
click the **Regional and Language** icon. On the **Formats** tab, select **Rromani** from the pull-down menu for "Format".

<p>
  <img src="images/locale.png" align="center" />
</p>

## Windows Un-installation

To remove the Romani keyboard or custom locale, open the **Control Panel,** click on **Programs and features**, then select **"Romani - IRU Standard"** (for the keyboard layout) or **"Custome Locale rom-RO"** (for the locale).

<p>
  <img src="images/uninstall.jpg" align="center" />
</p>





# MacOS Installation
1. Download the MacOS installer disk image [**here**.](Romani_IRU_Mac.dmg) and double-click the .dmg file to open it.

<p>
  <img src="images/macos_input.png" align="right" />
</p>

2. Drag "Romani - IRU Standard.bundle" to the folder on the left. "Rromani - IRU Standard" should now appear in the list of input sources at the top right of your screen. If it does not appear, or you do not see the input sources list, follow these directions:
   1. Choose the **Apple menu** > go to **System Preferences,** and then click the **Keyboard** preference pane.
   2. Click on the **Keyboard** tab and then select "Show keyboard and emoji viewers in menu bar".
   3. Click the **Input sources** tab. If the Romani keyboard does not appear in the list on the left, click the **+** button at the lower-left and select "Romany (Latin)" from the list of languages on the left, then click **"Add".**



# Keyboard Reference Guide

- Download the Windows keyboard reference PDF [**here**.](romani-keyboard-win.pdf) 
- Download the MacOS keyboard reference PDF [**here**.](romani-keyboard-mac.pdf) 

### Typing special characters
(English Keyboard)

| Character | Windows | Mac  |
|----|----|----|
| ʒ | ``  [  `` key | ``  [  `` key |
| θ | ``  ]  `` key | ``  ]  `` key |
| ç | ``  \ `` key | ``  \  `` key |
| ǎ | AltGr + a | Option + a |
| ě | AltGr + e | Option + e |
| ǐ | AltGr + i | Option + i |
| ǒ | AltGr + o | Option + o |
| ǔ | AltGr + u | Option + u |
| ś | ``  ;  `` key | ``  ;  `` key |
| ć | ``  '  `` key | ``  '  `` key | 
| ź | AltGr + z | Option + z |
| ä | AltGr + 2, then a | Option + 2, then a |
| ë | AltGr + 2, then e | Option + 2, then e |
| ï | AltGr + 2, then i | Option + 2, then i |
| ö | AltGr + 2, then o | Option + 2, then o |
| ü | AltGr + 2, then u | Option + 2, then u |
| à | AltGr + `, then a | Option + `, then a |
| è | AltGr + `, then e | Option + `, then e |
| ì | AltGr + `, then i | Option + `, then i |
| ò | AltGr + `, then o | Option + `, then o |
| ù | AltGr + `, then u | Option + `, then u |


**************
## Built With

* [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339) - Windows Keyboard Layout
* [Microsoft Locale Builder](https://www.microsoft.com/en-us/download/details.aspx?id=41158) - Windows Custom Locale
* [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) - Mac OSX Keyboard Layout

## Authors

* **Shaun Williams** - *Concept, creation* - Blog: [Beyond Karpaty](https://www.mutiny.net)

* **Ionel Cordovan** - *Design, consultation, testing*

* **George Sarău** - *Consultation, testing* - Website: [Minority Division, Romanian Ministry of Education](https://www.edu.ro/echipa%20minoritati)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details.
