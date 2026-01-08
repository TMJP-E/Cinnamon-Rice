# Cinnamon-Rice

A visual theme designed around the Sanrio character, **Cinnamoroll**, our favorite cloud doggy.

The theme is designed mainly with Linux desktops in mind, Android support is also planned for a future release, this documentation only covers the config files, software used, design choices, color pallete, icon pack, typographies and assets.

![Image here](path/to/image)

## Linux Ricing

*Ricing* is a term that can be understood as visual modifications of one's system, ranging from color changes on windows, borders and icons, the tools or software used, their elements and functionalities, etcetera. 
The first part of the theme will consist on a small guide to how the Linux side of ricing works for this specific project, refer to [MMR](https://github.com/TMJP-E/MegaHQ-MMR) for my own comprehensive guide on the topic.

### Components and tools

It is recommended that you read and familiarize yourself at least a tiny bit with the projects mentioned ahead, as they constitute the functionaility of our theme.

- [Hyprland](https://hypr.land/) - Dynamic tilling compositor for Wayland that allows for eye-candy and good special effects, including all utilities unless mentioned otherwise.
- [Alacritty](https://alacritty.org/) - Modern terminal emulator of choice thanks to how extensible and configurable it is.
- [ashell](https://malpenzibo.github.io/ashell/) - Status bar that has a similar feeling to those appearing in most Android devices.
- [HyprTile](https://hyprtile.org/) - Mega-Launcher for Hyprland that includes a lot of useful and QoL features.
- [Nemo](https://github.com/linuxmint/nemo) - File manager for Cinnamon.
- [wlogout](https://github.com/ArtsyMacaw/wlogout) - Logout menu.
- [Watershot](https://github.com/Kirottu/watershot) - Screenshotting utility (I've had problems with Flameshot before).
- [nwg-shell-config](https://github.com/nwg-piotr/nwg-shell-config?tab=readme-ov-file#nwg-hud) - GUI for configuring the composition on Hyprland.
- [hyprnotify](https://github.com/codelif/hyprnotify?tab=readme-ov-file) - Notification daemon.
- [hyprbars](https://github.com/hyprwm/hyprland-plugins/tree/main/hyprbars) - Title bars for applications.

### Design Choices

#### Look&Feel

[Material Design](https://m3.material.io/) is an important inspiration to take into account,the rounded semi-minimalist look supported by Android, guidelines for borders, images, spacing, focus, colors and more are used as a loose indication of where to take the design of this theme.

#### Color Palette

The [color palette](/Assets/Palette/MaterialColors.json) used is determined by [Matugen](https://github.com/InioX/matugen) using the [wallpaper](/Assets/Backgrounds/Cinamoroll-Horizontal.png), as it follows the color guides and generation that M3 uses, it is a light theme centered mainly on an opaque turquoise primary color, with complements for making interfaces.

A small preview of the color palette's main colors: 
<span style="color: #27638a">**Primary**</span>
, 
<span style="color: #50606e">**Secondary**</span>
, 
<span style="color: #65587b">**Tertiary**</span>
 and 
<span style="color: #f7f9ff">**Background**</span>
.

#### Icon Pack

The icon pack was made by me, using multiple Cinnamoroll assets from oficial sources and/or my creations/modifications accordingly, it is a Work In Progress and constant additions and changes are being made, it includes a cursor theme too.

#### Typography

Fonts are an interesting topic, you don't need anything outstanding to go along with any system, only a standard font you can look to constantly, maybe a system font and definitely something monospaced, as such, we have chosen three fonts to go along this system: [Playpen Sans](https://fonts.google.com/specimen/Playpen+Sans) for our system, [Sour Gummy](https://fonts.google.com/specimen/Sour+Gummy) for content and [Google Sans Code](https://fonts.google.com/specimen/Google+Sans+Code) for monospaced requirements.

#### Assets

All assets are listed on the corresponding [folder](/Assets/), they must all ressemble Cinnamoroll in one way or another, have great quality and resolution, and are named and used accordingly. Assets can be used to decorate menus and other UI elements.

Unless specified, I do not posess ownership of any of them, and they are used complying with Fair Use, they cannot be redistributed and all credits go to their respective aithors.

### Applying the rice




