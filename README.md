# Waybar

This repository contains my personal configuration files for Waybar, a highly customizable status bar for Wayland compositors like Sway and Hyprland. These configurations are designed to enhance productivity while maintaining a sleek and functional appearance.

## Preview

<p align="center">
  <img src="assets/preview.png"/>
</p>

## Features

- **Audio Controls**: Integrated PulseAudio audio controls using `pavucontrol`.
- **Network Status**: Displays Wi-Fi and Ethernet status with easy access to `nmtui`.
- **Bluetooth Controls**: Integrated blueman for bluetooth controls.
- **Bluelight Protection**: Module which uses hyprsunset to provide a warmer colour.
- **Logout Menu**: Includes a logout menu using wlogout.
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
- [PulseAudio](https://pulseaudio.org/) and `pavucontrol` for audio control
- [NetworkManager](https://wiki.archlinux.org/title/NetworkManager) and `nmtui` for network management
- [wlogout](https://aur.archlinux.org/packages/wlogout) for logout menu
- [hyprsunset](https://wiki.hyprland.org/Hypr-Ecosystem/hyprsunset/) for warmer colours
- [blueman](https://wiki.archlinux.org/title/Blueman) for bluethooth manager
- [Font Awesome](https://archlinux.org/packages/extra/any/ttf-font-awesome/) for fonts


- Hyprland or Sway (or another Wayland compositor)

## Contributing

These configurations are tailored to my preferences, but contributions and suggestions are welcome! Feel free to open an issue or submit a pull request.

## Acknowledgements

- [Waybar Documentation](https://github.com/Alexays/Waybar/wiki) for guidance on customization
- The open-source community for inspiration and solutions

Feel free to customize these configurations to suit your setup!
