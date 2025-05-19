Wallpaper Selector
A simple, sleek wallpaper picker for Linux (GNOME).
Pick your wallpaper fast — mouse or keyboard — and set it instantly!

Features
Clean GUI with yad

Supports JPG, JPEG, PNG

Keyboard & mouse navigation

Applies wallpaper instantly on GNOME

Minimal setup, zero hassle

Setup
Put wallpapers in ~/Pictures/wallpapers (create if missing)

Move script to ~/.local/bin/ and make executable:

bash
Copy
Edit
mv wallpaper-selector ~/.local/bin/  
chmod +x ~/.local/bin/wallpaper-selector
Install yad:

bash
Copy
Edit
sudo pacman -S yad     # Arch  
sudo apt install yad   # Ubuntu/Debian  
Run:

bash
Copy
Edit
wallpaper-selector
Keyboard Shortcut
Make your life easier:

Open Settings → Keyboard → Custom Shortcuts

Add shortcut:

Name: Wallpaper Selector

Command: /home/your_username/.local/bin/wallpaper-selector

Shortcut: e.g. Super + W

Press it, pick a wallpaper, done.

Feedback?
Made this just for fun.
Try it out, report bugs, suggest features!
Let’s make this better together.

🎨✨ Happy wallpaper hunting!

