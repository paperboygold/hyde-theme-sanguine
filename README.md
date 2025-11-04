# Sanguine - HyDE Theme

A dark, sophisticated theme for [HyDE (Hyprland Desktop Environment)](https://github.com/HyDE-Project/HyDE) featuring deep maroon, burgundy, and golden accents.

## Color Palette

- **Primary**: Maroon `#a52a2a`
- **Secondary**: Deep Red `#8b0000`
- **Accent**: Gold `#d4a753`
- **Background**: Dark Red-Grey `#120a0a`
- **Foreground**: Off-White `#fcf8f8`

## Features

- Custom Hyprland border colors with maroon/gold gradients
- Waybar theme with dark red-grey background
- Rofi launcher with maroon selections
- Kitty terminal color scheme with burgundy tones
- Kvantum Qt theme integration
- High-quality AI-upscaled wallpaper

## Installation

### Prerequisites

- [HyDE](https://github.com/HyDE-Project/HyDE) installed and configured
- Hyprland running

### Install Theme

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/hyde-theme-sanguine.git
cd hyde-theme-sanguine
```

2. Copy theme files to your HyDE config:
```bash
cp -r Configs/.config/hyde/themes/Sanguine ~/.config/hyde/themes/
```

3. Apply the theme:
```bash
hydectl theme set Sanguine
```

## Theme Components

- `hypr.theme` - Hyprland window borders, gaps, and blur settings
- `waybar.theme` - Status bar colors
- `rofi.theme` - Application launcher colors
- `kitty.theme` - Terminal color scheme
- `kvantum/` - Qt application theming
- `wallpapers/` - Theme wallpapers

## Customization

Edit the theme files in `~/.config/hyde/themes/Sanguine/` to customize colors:

- Hyprland borders: Edit `hypr.theme`
- Waybar colors: Edit `waybar.theme`
- Launcher colors: Edit `rofi.theme`
- Terminal colors: Edit `kitty.theme`

After making changes, reload the theme:
```bash
hydectl theme set Sanguine
```

## Credits

- Based on the [Decay Green theme](https://github.com/HyDE-Project/hyde-themes/tree/Decay-Green)
- Color scheme inspired by dark maroon and golden aesthetics
- Built for [HyDE](https://github.com/HyDE-Project/HyDE)

## License

MIT License - Feel free to modify and share!
