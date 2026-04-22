# If a new snap breaks then:
snap revert kate

# Copy shortcut into place
cp org.kde.kate.BACKUP_snap    /home/jp/.local/share/applications/org.kde.kate.desktop

# For Flatpak
cp org.kde.kate.BACKUP_flatpak /home/jp/.local/share/applications/org.kde.kate.desktop

# WARNING: A shortcut named org.kde.kate.desktop.XXXXXXX will still be read as a shortcut (2026-04-21)

