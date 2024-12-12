# Waybar

This repository contains my personal configuration files for Waybar, a highly customizable status bar for Wayland compositors like Sway and Hyprland. These configurations are designed to enhance productivity while maintaining a sleek and functional appearance.

## Features

- **Audio Controls**: Integrated PulseAudio audio controls using `pavucontrol`.
- **Network Status**: Displays Wi-Fi and Ethernet status with easy access to `nmtui`.
- **Custom Modules**: Includes power management and workspace modes tailored for Hyprland.
- **Theming**: Personalized themes for a visually appealing setup.

## Installation

To use these configuration files:

1. Clone the repository to your local machine:  
   `git clone https://github.com/ashwinmanoj97/Waybar.git`

2. Navigate to the cloned directory:  
   `cd Waybar`

3. Copy the configuration files to your Waybar config directory (usually `~/.config/waybar`):  
   `cp -r * ~/.config/waybar`

4. Restart your Wayland compositor to apply the new configuration.

## Dependencies

Ensure the following dependencies are installed:

- [Waybar](https://github.com/Alexays/Waybar)
- [PulseAudio](https://pulseaudio.org/) and `wpctl` for audio control
- [NetworkManager](https://wiki.archlinux.org/title/NetworkManager) and `nmtui` for network management
- Hyprland or Sway (or another Wayland compositor)

## Contributing

These configurations are tailored to my preferences, but contributions and suggestions are welcome! Feel free to open an issue or submit a pull request.

## Acknowledgements

- [Waybar Documentation](https://github.com/Alexays/Waybar/wiki) for guidance on customization
- The open-source community for inspiration and solutions

Feel free to customize these configurations to suit your setup!
