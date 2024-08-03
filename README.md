![logo](https://github.com/user-attachments/assets/2a0d50dc-60bf-4c85-b4d4-b87e19013db6)

# About

KantOS is a theme ported for OnionOS, which is inspired by the Kanto region of Pokémon.

The concept design was first created by [Tressley on muOS](https://github.com/Tressley/KantOS/tree/main) for the Anbernic handheld devices. I was a huge fan of it, and I'd like to express my appreciation to Tressley for creating the theme and also giving me permission to port it to OnionOS.

I have since heavily modified it to suit the vastly-different OnionOS architecture, and have included many of my own additions to the theme.

# Credits

- *Aemiii91* for letting me include their `Dot-art by Yoshi-kun` icon pack from the [Onion Theme Repo](https://github.com/OnionUI/Themes/blob/main/generated/icons_standalone/index.md)
- [Spriters-Resource](https://www.spriters-resource.com) for the Pokémon sprites
- [Yuji Oshimoto](http://www.04.jp.org/) for the `04b_03` font
- Pokémon Black/White 2 for the Virbank City OST

# Important Notes

- It is ***highly*** recommended to update your OnionOS to at least `v4.3.1-1` or higher, as it removes the text-shadow effect that's present on earlier versions which is incompatible with the font used here (see the [OnionOS Releases page](https://github.com/OnionUI/Onion/releases) or use the OTA feature within the Apps on your Miyoo Mini)
- On the wifi configuration page, the font color of the highlighted item as well as the font in the keyboard pop-up when you go to enter a wifi password are both *bugged*, since those appear to be set at the system-level and isn't something I can change through the config file
- **In case you have any existing theme overrides**, I recommend that you enable the `battery percentage` option with the following settings to replicate what's been set in the config file for the best UI experience:

Go to `Apps > Tweaks > Appearance > Theme overrides > Battery Percentage`

```json
"Visible": set to "-" (the theme config will turn it on by default)
"Font family": set to 'Exo-2-Bold-Italic_Universal'
"Font size": 18 px
"Text alignment": Left
"Fixed position": off
"Horizontal/Vertical offset": both set to 0 or off
```

# Download

You can find the latest ZIP file on the [Releases](https://github.com/antonlabz/KantOS/releases) page.

# Installation

- Place the downloaded ZIP file into the `Themes` folder of your SD card
- Apply the theme by going to `Apps > Themes` and selecting it

# What is the difference between `Ver. A` and `Ver. B`?

`Ver. A` is the original design concept based off the muOS theme which has the 3 primary menus as buildings, while the remaining menus are minimal icons.

`Ver. B` is a more overworld-focused theme, and has transformed the 3 aforementioned minimal icons to overworld variants.

Please see the next section which showcases both.

# Screenshots

#### Version A

![original](https://github.com/user-attachments/assets/f01a8aea-fd6a-4de7-85e6-4ca79a168bbe)

#### Version B

![overworld](https://github.com/user-attachments/assets/99e8d3f5-b592-4a6b-ae71-2e05cc8a5a9c)

#### Settings
![settings](https://github.com/user-attachments/assets/027e7bcd-edc4-44dc-b3db-cad3d9a01620)

#### Games
![MainUI_012](https://github.com/user-attachments/assets/236ee89b-726b-4de2-8f31-1fc6d8c972fd)

#### Boot Screen
![bootScreen](https://github.com/user-attachments/assets/a7d30d8a-e063-450b-9886-08cf51e18131)

#### Low Battery
![lowBat](https://github.com/user-attachments/assets/40feca0d-f9d9-4b00-acd3-f72491f2d948)

#### Charging Animation
![charging](https://github.com/user-attachments/assets/15dfebf1-7684-4344-901e-03d14085d978)

#### Power Off + Save
![Screen_Off_Save](https://github.com/user-attachments/assets/2e0cc05f-de3c-4c0e-b57e-64bf2516207b)

#### Power Off
![Screen_Off](https://github.com/user-attachments/assets/c4bdab6a-4962-4a36-8059-b307de227a6d)

#### GameSwitcher
![GameSwitcher_000](https://github.com/user-attachments/assets/3a242d26-fed9-4d9d-bc6d-28fc0fdcc186)
