# Collection of my Dotfiles & Scripts

## Self-written scripts

Most of these scripts feature a help menu. You can view usage instructions by opening the script to read the comments or by running it with the -h or --help flags.

- clearPacman - Searches for and deletes orphan packages *(Inspired by [bluemi](https://github.com/Bluemi/std_utils/tree/master/clear-pacman))*
- goto - Navigates you faster through the terminal using aliases *(Inspired by [bluemi](https://github.com/Bluemi/std_utils/tree/master/goto))*
- import-playlist - Downloads YouTube Music playlists 
- monitorMode - When using Hyprland as the window manager this script decides whether to extend or mirror the main screen
- screenrecord - Records the entire screen or a selected region with internal/microphone audio support.
- screenshot - Takes screenshots and allows simple editing before saving
- wlan - CLI Wi-Fi manager. Uses iwctl under the hood to scan for networks and connect to them.
- yallah - Fast way to git add, commit and push to a repository

- install-bin - Moves all of the scripts above into the users ./local/bin folder

## Webapps

Add this line to your shell configuration (.bashrc or .zshrc)

```bash
export BROWSER="vivaldi" # Or firefox, chromium etc.
```


- calendar - Google Calendar
- drive - Google Drive
- github - Github
- gmail - Gmail
- slack - Slack
- todo - Todoist
- whatsapp - Whatsapp Web
- yt - Youtube

## Dotfiles

Matugen (Color Generator)
- Used to generate and maintain a unified color palette based on wallpapers across specified tools and desktop elements.

Neovim (Terminal Editor)
- Complete IDE-like configuration. Includes styling, custom keybindings, plugin management, and LSP support for coding.
