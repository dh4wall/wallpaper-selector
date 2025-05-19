<h1 align="center">Wallpaper Selector</h1>
<h3 align="center">A Simple & Fast Wallpaper Picker for GNOME on Linux</h3>

<h3 align="left">Installation</h3>
<p align="left">
  1. Add wallpapers to <code>~/Pictures/wallpapers</code>:<br>
      <code>mkdir -p ~/Pictures/wallpapers</code><br><br>
  2. Install <code>yad</code> and <code>variety</code>:<br>
      <code>sudo pacman -S yad variety</code>  # Arch<br>
      <code>sudo apt install yad variety</code>  # Ubuntu/Debian<br><br>
  3. Move the script and make it executable:<br>
      <code>mv wallpaper_selector.sh ~/.local/bin/wallpaper-selector</code><br>
      <code>chmod +x ~/.local/bin/wallpaper-selector</code>
</p>

<h3 align="left">Usage</h3>
<p align="left">
  Run the script:<br>
      <code>wallpaper-selector</code><br>
  Double-click a wallpaper name to set it instantly.
</p>

<h3 align="left">Keyboard Shortcut</h3>
<p align="left">
  1. Go to <strong>Settings → Keyboard → Custom Shortcuts</strong>.<br>
  2. Add a new shortcut:<br>
      - <strong>Name</strong>: Wallpaper Selector<br>
      - <strong>Command</strong>: <code>/home/your_username/.local/bin/wallpaper-selector</code> (replace <code>your_username</code>)<br>
      - <strong>Shortcut</strong>: e.g., <code>Super + W</code>
</p>

<h3 align="left">Feedback</h3>
<p align="left">
  Got ideas or issues? Let me know!<br>
  Happy wallpaper picking!
</p>

<div align="center">
  <p>Built by Dhawal Shinde</p>
</div>
