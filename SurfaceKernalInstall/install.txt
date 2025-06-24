wget -qO - https://raw.githubusercontent.com/linux-surface/linux-surface/master/pkg/keys/surface.asc | sudo pacman-key --add -
sudo pacman-key --finger 56C464BAAC421453   # erstellt den fingerprint
sudo pacman-key --lsign-key 56C464BAAC421453  # sagen pacman, dass er diesem Schlüssel vertrauen kann