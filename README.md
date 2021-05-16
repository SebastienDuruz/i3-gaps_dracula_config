# i3-gaps_dracula_config
My current configuration for i3-gaps. Nothing too fancy, I tried to makes it the easiest to reproduce for a further installation.
Remember that I have [Gnome_40] installed, some configurations could work differently with your configuration !

# Exemple results
![Screenshot_1](https://user-images.githubusercontent.com/40761875/118363213-9b953900-b593-11eb-9085-06f220b9946e.png)
![Screenshot_2](https://user-images.githubusercontent.com/40761875/118364670-bd91ba00-b599-11eb-9f5c-4f37e6251680.png)
![Screenshot_3](https://user-images.githubusercontent.com/40761875/118363441-abf9e380-b594-11eb-92b3-c5ab4e931f9a.png)
![Screenshot_4](https://user-images.githubusercontent.com/40761875/118363621-83beb480-b595-11eb-8d01-bb2c989181bd.png)

# How to install
## Dependencies
Make sure you have theses packages installed : 
* I3-gaps -> https://github.com/Airblader/i3
* Bumblebee-status -> https://github.com/tobi-wan-kenobi/bumblebee-status
* Rofi -> https://github.com/davatorium/rofi
* Picom -> https://github.com/yshui/picom
* Nitrogen -> https://github.com/l3ib/nitrogen
* Gnome-Terminal -> https://github.com/GNOME/gnome-terminal
* Nautilus -> https://github.com/GNOME/nautilus
## Config file
* Clone git content
```
git clone https://github.com/Smour/i3-gaps_dracula_config.git
cd i3-gaps_dracula_config
```
* Make sure you have a copy of your actual config file before doing anything !
* Copy the file .config/i3/config to ~/.config/i3/config
```
cp .config/i3/config ~/.config/i3/config
```
## Wallpaper
* Copy the file inside Wallpaper folder to the desired destination
```
cp Wallpaper/dracula.png DESIRED_DESTINATION
```
* Run nitrogen and apply the correct wallpaper (will be automaticaly setup each time i3 start)
## Dracula themes
* VIM -> https://draculatheme.com/vim
* Visual Studio Code -> https://draculatheme.com/visual-studio-code
* Gnome Terminal -> https://draculatheme.com/gnome-terminal
* GTK / Icons -> https://draculatheme.com/gtk
* Rofi -> https://draculatheme.com/rofi
