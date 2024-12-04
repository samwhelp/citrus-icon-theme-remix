

# Home

> [citrus-icon-theme-remix](https://github.com/samwhelp/citrus-icon-theme-remix)




## Orginal / Citrus-icon-theme

* [Pling](https://www.pling.com/p/1334044)
* [GitHub](https://github.com/yeyushengfan258/Citrus-icon-theme)

> install all

``` sh
git clone https://github.com/yeyushengfan258/Citrus-icon-theme.git

cd Citrus-icon-theme

mkdir -p ../icons

./install.sh -a -d $(pwd)/../icons

cd "${OLDPWD}"
```




## Another

| Another |
| ------- |
| [citrus-icon-theme](https://github.com/zayronxio/citrus-byzayron) |




## Remix

| Icon Theme | Inherits |
| ---------- | -------- |
| [Citrus-red](https://github.com/samwhelp/citrus-icon-theme-remix/tree/main/icons/Citrus-red) | [Inherits=Numix-Circle-Light,Numix-Light,Papirus-Light,Adwaita,hicolor](https://github.com/samwhelp/citrus-icon-theme-remix/blob/main/icons/Citrus-red/index.theme#L4) |
| [Citrus-red-dark](https://github.com/samwhelp/citrus-icon-theme-remix/tree/main/icons/Citrus-red-dark) | [Inherits=Numix-Circle,Numix,Papirus-Dark,Adwaita,hicolor](https://github.com/samwhelp/citrus-icon-theme-remix/blob/main/icons/Citrus-red-dark/index.theme#L4) |


> install red

``` sh
git clone https://github.com/yeyushengfan258/Citrus-icon-theme.git

cd Citrus-icon-theme

mkdir -p ../icons

./install.sh -red -d $(pwd)/../icons

cd "${OLDPWD}"
```

> adjust Inherits for Citrus-red

``` sh
value="Numix-Circle-Light,Numix-Light,Papirus-Light,Adwaita,hicolor"
index_theme_file_path="icons/Citrus-red/index.theme"
sed -i "s|^Inherits=.*|Inherits=${value}|g" "${index_theme_file_path}"
```

> adjust Inherits for Citrus-red-dark

``` sh
value="Numix-Circle,Numix,Papirus-Dark,Adwaita,hicolor"
index_theme_file_path="icons/Citrus-red-dark/index.theme"
sed -i "s|^Inherits=.*|Inherits=${value}|g" "${index_theme_file_path}"
```

> [apply case](https://github.com/samwhelp/deb-recipe/blob/main/recipe/cook-appearance-citrus-icon-theme/cook-appearance-citrus-icon-theme/asset/installer.sh#L71-L77)




## Inherits Depends


### Debian Package

| Debian Package |
| -------------- |
| [numix-icon-theme-circle](https://packages.debian.org/stable/numix-icon-theme-circle) |
| [numix-icon-theme](https://packages.debian.org/stable/numix-icon-theme) |
| [papirus-icon-theme](https://packages.debian.org/stable/papirus-icon-theme) |


> run to install

``` sh
sudo apt-get install numix-icon-theme-circle numix-icon-theme papirus-icon-theme
```


| Debian Package |
| -------------- |
| [adwaita-icon-theme](https://packages.debian.org/stable/adwaita-icon-theme) |
| [hicolor-icon-theme](https://packages.debian.org/stable/hicolor-icon-theme) |


> run to install

``` sh
sudo apt-get install adwaita-icon-theme hicolor-icon-theme
```


| Debian Package |
| -------------- |
| [gnome-icon-theme](https://packages.debian.org/stable/gnome-icon-theme) |
| [breeze-icon-theme](https://packages.debian.org/stable/breeze-icon-theme) |


> run to install

``` sh
sudo apt-get install gnome-icon-theme breeze-icon-theme
```




## Link

| Link |
| --- |
| Papirus Development Team / [papirus-icon-theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) |
| Numix Project / [numix-icon-theme](https://github.com/numixproject/numix-icon-theme) |
| KDE Invent / [breeze-icon-theme](https://invent.kde.org/frameworks/breeze-icons) |
| [demo-wallpaper-collection](https://github.com/samwhelp/demo-create-debian-package/tree/main/demo/wallpaper-collection/wallpaper-collection/demo-wallpaper-collection) |
| [cook-appearance-citrus-icon-theme](https://github.com/samwhelp/deb-recipe/tree/main/recipe/cook-appearance-citrus-icon-theme/cook-appearance-citrus-icon-theme) |
| [canta-icon-theme-remix](https://github.com/samwhelp/canta-icon-theme-remix) |
