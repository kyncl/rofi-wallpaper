# rofi-wallpaper
Nothing fancy-schmancy just using rofi to set new wallpaper


## Dependencies
### hard dependencies
<ul>
<li>rofi</li>
</ul>  

### light dependencies (more in section tweaks)

<ul>
<li>pywal</li>
<li>swww</li>
</ul>

## Installation/Usage

```bash
git clone https://github.com/kyncl/rofi-wallpaper/
cd rofi-wallpaper
chmod +x rofi-wallpaper
./rofi-wallpaper path/to/wallpapers
```
after that you can put the script in <code>/usr/local/bin/</code> or <code>~/.local/bin</code> to run it anywhere

## Tweaks
function <code>set_wallpaper()</code> is called after selection (you can remove pywal part or change swww to something you use)  
