# Hammerspoon Weather Menubar

Load weather information from [[wttr.in]] and display in the menubar.

## Loading the sppon

Clone this repo in `~/.hammerspoon/Spoons/`. (After doing so, the path to this
readme should be `~/.hammerspoon/Spoons/WttrWeather.spoon/readme.md`.

Now load the spoon from your Hammerspoon config:

```lua
hs.loadSpoon('WttrWeather')
spoon.WttrWeather:start({})
```

# Configuration

- `clickUrl`: URL to open on click (default: Open Weather)
- `format`: Wttr.in format string (defaul "%C+%t")
- `interval`: Interval in seconds to refresh the menu (default 600)
