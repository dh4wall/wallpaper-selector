Wallpaper Selector
A simple, sleek wallpaper picker for Linux (GNOME).Pick your wallpaper fast—mouse or keyboard—and set it instantly!
Features

Clean GUI with yad  
Supports JPG, JPEG, PNG  
Keyboard & Mouse Navigation  
Instant Wallpaper Application on GNOME  
Minimal Setup, Zero Hassle

Setup

Prepare Your WallpapersPut your wallpapers in ~/Pictures/wallpapers. If the directory doesn’t exist, create it:  
mkdir -p ~/Pictures/wallpapers


Install Dependencies  

Install yad (for the GUI):  sudo pacman -S yad     # Arch
sudo apt install yad   # Ubuntu/Debian


Install variety (to set wallpapers):  sudo pacman -S variety     # Arch
sudo apt install variety   # Ubuntu/Debian




Move and Make the Script ExecutableMove the wallpaper_selector.sh script to ~/.local/bin/ and make it executable:  
mv wallpaper_selector.sh ~/.local/bin/wallpaper-selector
chmod +x ~/.local/bin/wallpaper-selector


Run the ScriptLaunch the wallpaper selector:  
wallpaper-selector



Keyboard Shortcut
Make your life easier by setting up a keyboard shortcut:

Open Settings → Keyboard → Custom Shortcuts (or search for "Keyboard Shortcuts" in GNOME Settings).
Add a new shortcut:
Name: Wallpaper Selector
Command: /home/your_username/.local/bin/wallpaper-selector (replace your_username with your actual username)
Shortcut: e.g., Super + W


Press your shortcut, pick a wallpaper, and you’re done!

Usage

A yad window will pop up showing a list of wallpaper names from ~/Pictures/wallpapers/.
Double-click a wallpaper name to set it as your GNOME background instantly.
Use the search bar (start typing) or arrow keys to navigate the list.

Feedback
This project was made just for fun!Try it out, report bugs, or suggest features. Let’s make this better together!Feel free to reach out or contribute ideas.
🎨✨ Happy wallpaper hunting!
