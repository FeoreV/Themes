
# FVUI

## Blur is the new black


## Releases
   [WebSite](https://feorev.github.io/) (Soon)
 - [Discord](https://betterdiscord.app/theme/FVUI)
 - [Chrome](https://github.com/FeoreV/Themes/releases/tag/chrome) 
 
# Screenshots

## Subthemes

#### Light theme is also supported

### Default
![Default](https://feorev.github.io/Themes/Discord/assets/ReadMe/Default.png)
### WIN11 (custom image supported)
![WIN11](https://feorev.github.io/Themes/Discord/assets/ReadMe/WIN11.png)
### Mica
![Mica](https://feorev.github.io/Themes/Discord/assets/ReadMe/Mica.png)

## Addons
### MaterialYou
![MaterialYou](https://feorev.github.io/Themes/Discord/assets/ReadMe/MaterialYou.png)
### ModularDesign
![ModularDesign](https://feorev.github.io/Themes/Discord/assets/ReadMe/ModularDesign.png)
# Variables

To change variables, find them in the theme file using any text editor. 

### Example:
```

:root{
    --color3: 0, 0, 255;
    --DarkBG: url(https://example.com/YourBG.png);
    ...
}
```
## Subthemes 

### Colors (only in RGB)
|Colors     |Dark       |Light      |Description|
|-----------|-----------|-----------|-----------|
| color1    | ![#1e2832](https://via.placeholder.com/10/1e2832?text=+) 30, 40, 50 | ![#d3cce3](https://via.placeholder.com/10/d3cce3?text=+)  211, 204, 227 |Additional BG|
| color2    | ![#091218](https://via.placeholder.com/10/091218?text=+) 9, 18, 24 | ![#dbdbdb](https://via.placeholder.com/10/dbdbdb?text=+) 219, 219, 219 |Background|
| color3    | ![#2378c8](https://via.placeholder.com/10/2378c8?text=+) 35, 120, 200 | ![#60cdff](https://via.placeholder.com/10/60cdff?text=+) 96,205,255 |Additional accent|
| color4    | ![#3f2b96](https://via.placeholder.com/10/3f2b96?text=+) 63, 43, 150 | ![#3f2b96](https://via.placeholder.com/10/3f2b96?text=+) 63, 43, 150 |Gradient Color|

### WIN11 (Background can be changed)

|Variables  |Value                                                                     |Description             |
|-----------|--------------------------------------------------------------------------|------------------------|
|--DarkBG   |url(https://feorev.github.io/Themes/Discord/assets/Wallpapers/dark.avif); |Link to background image|
|--LightBG  |url(https://feorev.github.io/Themes/Discord/assets/Wallpapers/light.avif);|Link to background image|
|--OpacityBG|100% or 1;                                                                |Background opacity      |
|--BlurBG   |0px                                                                       |Background blur         |

### Mica

|Variables  |Value        |Description             |
|-----------|-------------|------------------------|
|--BGcolor  |var(--color2)|Background color (In RGB (not RGBA))        |
|--BGopacity|40% or 0.4   |Background opacity (0-100% or 0-1)      |

## Addons

### Trash

None - hide elements

unset - show elements
|Variables    |Recomended value|Description             |
|-------------|----------------|------------------------|
|--nitro      |**None** or unset|Removes unnecessary items from a category|
|--contextmenu|**None** or unset|Removes unnecessary items from a category|
|--profile    |**None** or unset|Removes unnecessary items from a category|
|--chat       |**None** or unset|Removes unnecessary items from a category|
|--other      |**None** or unset|Removes unnecessary items from a category|

### Material You
[ColorPicker](https://g.co/kgs/83i83K)
|Variables     |Dark (First 2 HSL values)|Light (First 2 HSL values)|Description|
|--------------|-------------------------|--------------------------|-----------|
|--accentcolor |210, 68%                 |199, 100%                 |Adjusts the theme color scheme to accentcolor|

### Modular Design (temporarily may cause visual problems with blur)

MainModules (ServerList/ChatArea/FriendList/Settings)
|Variables     |Value                              |Description             |
|--------------|-----------------------------------|------------------------|
|--outline     |3px                                |Outline size (px)|
|--outlineCLR  |var(--color03)                     |Outline color (any color)|
|--outlineBR   |16px                               |Outline border-radius (rounding/px)|
|--outlineMG   |2rem                               |Outline margin (px/rem)|
|--outlineBS   |15px var(--outlineCLR)             |Outline box-shadow (size(px) / color (default is - outline colour))|
|--outlineBG   |unset                              |Modular modules background (color)|
|--outlineBLUR |0                                  |Modular modules background blur (px)|

AdditionalModules (ServerList/ChatArea/FriendList/...). Default - disabled. Set --outline2 and --outlineBS2
|Variables     |Value                              |Description             |
|--------------|-----------------------------------|------------------------|
|--outline2     |0                            |Outline size (px)|
|--outlineCLR2  |var(--outlineCLR)                     |Outline color (any color)|
|--outlineBR2   |var(--outlineBR)                               |Outline border-radius (rounding/px)|
|--outlineMG2   |var(--outlineMG)                               |Outline margin (px/rem)|
|--outlineBS2   |0          |Outline box-shadow (size(px) / color (default is - outline colour))|
|--outlineBG2   |unset                              |Modular modules background (color)|
|--outlineBLUR2 |0                                  |Modular modules background blur (px) (Not recomended)|

## Support

To suggest an innovation or report a bug, contact the [Discord Server](https://discord.gg/baEMQkgswT)  or DM (feorev)
