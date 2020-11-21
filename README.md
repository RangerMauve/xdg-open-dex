# xdg-open-dex
Run .desktop files with dex and xdg-open


Was going to put a bunch of stuff here, but you should follow this guide instead: https://github.com/jceb/dex/issues/29

tl;dr

```
sudo apt-get install dex

dex -c `which dex` -t ~/.local/share/applications/

nano ~/.config/mimeapps.list
# Add this at the end of the [Added Associations] section
application/x-desktop=dex.desktop;
```
