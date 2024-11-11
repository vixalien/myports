## upstream(ing/ed)

- [ ] elementary-stylesheet
- [ ] elementary-icon-theme
- [ ] elementary-camera
- [ ] elementary-calculator
- [ ] elementary-music
- [ ] elementary-terminal

## others

- [x] appcenter
- [x] elementary-files
- [x] elementary-settings-daemon
- [x] pantheon-dock
- [x] elementary-shortcut-overlay
- [x] gala
- [x] switchboard
- [ ] switchboard-plug-about
- [x] switchboard-plug-applications
- [x] switchboard-plug-bluetooth
- [x] switchboard-plug-datetime
- [x] switchboard-plug-display
- [x] switchboard-plug-keyboard
- [x] switchboard-plug-locale
- [x] switchboard-plug-mouse-touchpad
- [x] switchboard-plug-network
- [ ] switchboard-plug-notifications
- [x] switchboard-plug-onlineaccounts
- [ ] switchboard-plug-pantheon-shell
- [ ] switchboard-plug-parental-controls
- [ ] switchboard-plug-power
- [x] switchboard-plug-printers
- [x] switchboard-plug-security-privacy
- [ ] switchboard-plug-sharing
- [x] switchboard-plug-sound
- [x] switchboard-plug-useraccounts
- [ ] switchboard-plug-wacom
- [x] gala
- [x] pantheon-applications-menu
- [x] wingpanel
- [ ] pantheon-quick-settings
- [x] wingpanel-indicator-bluetooth
- [x] wingpanel-indicator-network
- [x] wingpanel-indicator-network

## 

- use the elementary-icon-theme
- rename to elementary-music
- elementary-stylesheet

## blockers

- switchboard-plug-power needs 'io.elementary.desktop.wingpanel.power'

- switchboard-plug-sharing needs elementary-bluetooth-proxy ('io.elementary.desktop.bluetooth')
- switchboard-plug-notifications needs elementary-notifications ('org.pantheon.desktop.gala.notifications')
- elementary-files needs contractor
- elementary-files might need  portals
- elementary-session might depend on elemebetterntary-default-settings
- elementary-videos needs newer valac for null-terminated mishaps
- elementary-mail probably same issue as above
- elementary-calendar probably same issue as above
- elementary-tasks probably same issue as above

- switchboard-plug-parental-controls needs 'malcontent' (link here)
- switchboard-plug-parental-controls needs systemd https://github.com/elementary/switchboard-plug-parental-controls/issues/197
- switchboard-plug-about needs older fwupd
- switchboard-plug-pantheon-shell needs (granite7>7.5.0) (https://gitlab.alpinelinux.org/alpine/aports/-/merge_requests/73437)
