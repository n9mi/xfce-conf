# xfce-conf
xfce configuration for my personal device. it's a desperate attempt to replicate something just like [this](https://payload.cargocollective.com/1/17/564825/8876514/monitor_screens_006_901.jpg) and [this](https://payload.cargocollective.com/1/17/564825/8876514/monitor_screens_016_901.jpg).

## Copy theme and icons
```
sudo cp -r bluesky-dark /usr/share/themes
sudo cp -r fluent-round-dark /usr/share/themes
sudo cp -r kora-icons /usr/share/icons
```

## Font
```
sudo apt install fonts-jetbrains-mono
```
Set Appearance > Fonts as: 
- Default font: JetBrains Mono Medium - 9
- Default monospace font: JetBrains Mono ExtraLight - 10

## Window manager
For window manager, I used [Fluent GTK theme](https://github.com/vinceliuice/Fluent-gtk-theme).
- Font: JetBrains Mono Bold - 9

## Appearance
For Appearance > Style, I used [Bluesky GTK theme](https://github.com/i-mint/bluesky)

## Icon
I used [Kora](https://www.xfce-look.org/p/1256209/) 

## Panel
- Arrange panel items to be like this:
  <img src="https://github.com/n9mi/xfce-conf/blob/master/panel/panel_preference.png?raw=true" alt="Panel item">
- For panel styling, I modificate from this [xfce-rice theme](https://github.com/diws1/xfce-rice).
- Rewrite .config/gtk-3.0/gtk.css as [gtk.css](https://github.com/n9mi/xfce-theme/blob/main/gtk.css).

## Terminal
- Font: JetBrains Mono ExtraLight - 12
- Columns: 86
- Rows: 25

## Conky
```
sudo apt install conky-all
```
Rewrite /etc/conky/conky.conf as [conky.conf](https://github.com/n9mi/xfce-theme/blob/main/conky.conf)

## Wallpaper
```
sudo cp wallpaper.jpg /usr/share/xfce4/backdrops
```

## Result
<img src="https://github.com/n9mi/xfce-conf/blob/master/result/result.png?raw=true" alt="Result">
