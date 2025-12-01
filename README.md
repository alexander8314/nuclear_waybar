# nuclear_waybar
Reactor-themed Waybar for Arch Linux + Hyprland

## Features
- **Blue reactor aesthetic**: Glowing cyan theme with pulsing effects and meltdown warnings at critical thresholds
- **Vertical resource monitor**: Large right-side bar (200px) displaying CPU, RAM, disk, and multi-scale temperature readings
- **Real-time system stats**: Live monitoring with 2-5 second intervals and visual alerts when resources spike
- **Hyprland integration**: Native workspace support with reactor-core launcher button
- **Minimal design**: Clean, functional layout focused on essential system health metrics

## Installation
```bash
cd ~/.config/waybar
git init
git remote add origin https://github.com/alexander8314/nuclear_waybar.git
git pull origin main
killall waybar && waybar &
```