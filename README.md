✨ Wallpaper Selector ✨
A lightweight and fast wallpaper picker for GNOME on Linux.Pick your wallpaper and set it instantly! 🚀

🔧 Setup

Prepare WallpapersAdd your wallpapers (JPG, PNG, JPEG) to ~/Pictures/wallpapers:  
mkdir -p ~/Pictures/wallpapers


Install DependenciesInstall yad and variety:  
sudo pacman -S yad variety  # Arch
sudo apt install yad variety  # Ubuntu/Debian


Setup the ScriptMove the script to ~/.local/bin/ and make it executable:  
mv wallpaper_selector.sh ~/.local/bin/wallpaper-selector
chmod +x ~/.local/bin/wallpaper-selector


Add Styling for the PickerCreate a CSS file for the Yad window:  
mkdir -p ~/.config/yad
nano ~/.config/yad/style.css

Paste the CSS (see the script section below), save, and exit.



🎨 Usage
Run the script:  
wallpaper-selector


A styled window will show your wallpaper names.  
Double-click a name to set it as your wallpaper. ✅


⌨️ Keyboard Shortcut

Go to Settings → Keyboard → Custom Shortcuts.  
Add a new shortcut:  
Name: Wallpaper Selector  
Command: /home/your_username/.local/bin/wallpaper-selector (replace your_username)  
Shortcut: e.g., Super + W




💡 Feedback
Got ideas or issues? Let me know! Let’s make this better together.  
🌟 Happy wallpaper picking!
